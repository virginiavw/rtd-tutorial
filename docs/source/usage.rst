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

::

   These properties will be used to name the output of this script (the metadata). 
   The "Preview output prefix" shows what the file name will look like. As shown, all but “User Initials” will be used.
   However, the user initials will be saved in the metadata file so that, if needed, the person who edited the file can be found.

.. image:: images/output_prefix.png
  :width: 400

Step 5: Using the scroll bar, as well as the frame jump buttons, navigate to the start of your first trial 
"""""""""""

.. image:: images/Findingfirstframe.gif
  :width: 700

Step 6: Click "Get trim points" 
"""""""""""

::

   Starting from your current frame, the script will load 2-minute trials separated by 2 minute intervals.
   This should correspond with the start/end of the trials in your video


.. image:: images/get_trial_timepoints.png
  :width: 700


