Usage
=====

.. _installation:

Installation
------------

To use the Basic Trimmer, first install it through ?:

.. code-block:: console

   hmm!

Part 1: Getting the Trim Points
----------------
Step 1. Run "basic_trimmer.py". When the GUI opens up, it should look like the following: 
"""""""""""

.. image:: images/GUI_blank.png
  :width: 700

Step 2: Navigate to the folder holding the videos to trim.
"""""""""""

.. image:: images/browse.png
  :width: 700

Step 3. Click "Next Video" to load in the first video you are going to trim. 
"""""""""""

.. image:: images/next_video_button.png
  :width: 700

Your screen should look like the following

.. image:: images/video_loaded.png
  :width: 700

Step 4. Click to change these properties. 
"""""""""""
Change the properties of the video by clicking on each box and typing in the appropriate information
::

   These properties will be used to name the output of this script (the metadata). 
   The "Preview output prefix" shows what the file name will look like. As shown, all but “User Initials” will be used.
   However, the user initials will be saved in the metadata file so that, if needed, the person who edited the file can be found.

.. image:: images/output_prefix.png
  :width: 400

Step 5: Navigate to first trial 
"""""""""""

Using the scroll bar, as well as the frame jump buttons, navigate to the start of your first trial 

.. image:: images/Findingfirstframe.gif
  :width: 700

Step 6: Click "Get trim points" 
"""""""""""

::

   Starting from your current frame, the script will load 2-minute trials separated by 2 minute intervals.
   This should correspond with the start/end of the trials in your video


.. image:: images/get_trial_timepoints.png
  :width: 700

Step 7 - Step (a lot probably)
"""""""""""

a) Click "GOTO" to jump to the appropriate "Trim Start" point
b) Scroll/use frame buttons until you find the end frame of interest. In this example, it is when the reward is introduced. The trial starts (as seen above) at 10:16. The end frame of interest occurs at 10:54

.. image:: images/GOTO.png
  :width: 700

c) Now, click the appropriate “Trim end” white box. Your current frame timestamp will replace the previous one
d) Click the appropriate “Add trim pts Label” to type in your label
e) Click the “+” button to add the trim point to the list at the bottom. 
::

Notice that the current frame moves from the end to the start, and that the end now has the original ending point. This is so that the next trim point can be found after this clip. 

f) To record the start time of the next clip, navigate to the desired starting frame using the scroller/buttons and then click the appropriate “Trim start” white box.
g) Repeat this process as needed within a trial. If all the time is used (trim start > trim end), then the text will appear red
