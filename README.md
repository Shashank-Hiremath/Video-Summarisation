# Vedio-Summarisation2
Given an input video its summaries the video,reducing number of frames,man power.So that it is easy to analyse the video,and pre-processing would be less costlier

Step 1)</br>
Add a sample video to your present working directory where the python files are cloned
Step 2)</br>
Run summarisation_trail.py file with the changes as mentoined below
->change the video file name to name of the video that you had saved in step1.
step 3)</br>
After step2 your current working directory will be filled with frames named photoo0.png,photoo1.png ...... photoo(summarised_framecount).png
->Now make changes in the "while" condtion, i'e "while count<673"
change the value of 673 to summarised_framecount which is available after step2.

</br>
Note:
In summarisation_trail.py there are two variables which may be changed according to the requirement.</br>
1) if cv2.contourArea(c)<400</br>
2)if detection_count>0
