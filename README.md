# GRAD521_Pfeiffer2025

This is a data management plan (DMP) for the GRAD521 course at Oregon State University (OSU).

## Research Context

The ocean is a vast and dangerous environment that is known to be largely unexplored. While there exist mapping tools for the ocean floor (e.g., sonar), these technologies don’t allow physical interaction with the environment. If one then wishes to gather physical samples or gather debris from the ocean floor, a human diver would need to dive at extreme depths to complete the task. 

However, if we wish to avoid putting a human life in danger, an alternative method would be to control a robot so the human can perform the task from a relatively safer place. Unfortunately, controlling an underwater robot is easier said than done since low-lighting conditions, murky waters, and aggressive underwater currents make it hard to interpret sensor information. This brings up a question regarding what sensory information to gather from the robot and how the information can best be displayed to the commander.

Since the low-lighting and murky water both impair visual clarity, one possibly helpful piece of sensory information would be tactile sensors, which allow the human to gain a sense of what the robot is touching. This brings us to our main research question, which is as follows: How do different display types of tactile information interact with different grasps on objects to impact a human’s ability to correctly identify the success of a grasp? An example of what we are looking for with this question is whether a display would be better for detecting if an object is slipping from the robot’s grasp while another would be better at identifying when an object is securely grasped).

In order to answer this question, we will be showing human subjects pre-recorded grasps with different tactile displays and a camera feed that is artificially impaired by adding a significant blur to it. The impaired camera feed is done so that users will have to rely on the tactile information to make their decision about the success of a grasp.

## Dataset Description

### Human Subjects Data

The first dataset will consist of all relevant human subject data. This includes demographic information (age, sex, race, home country), general attitudes towards robots, familiarity with robots, per-trial information (accuracy, confidence, reaction-time), and the overall task information (subjective task-load rating). All data will be stored in a spreadsheet alongside a corresponding subject ID and task version ID to match the subject and display to the data obtained. The data will be collected and saved to a spreadsheet as the user interacts with the computer software by manually entering the information or having it collected automatically throughout the experiment.

### Metadata

The second dataset will consist of data for conducting the test (and available for replication of the study). This will be the metadata, which includes the code for displaying the interface, the recordings of the camera feed (as video files) and tactile feed (as spreadsheets) for each grasp, and the code for all analyses performed in the study. This data will be collected prior to the study by storing recorded sensory feeds from a robotic arm that is currently in the lab.

## Dataset Size

The sizes of the two datasets only slightly differ. The human subjects dataset is expected to be on the order of MB (100-999 MB) since we anticipate testing around 40 participants. However, the metadata dataset will be slightly larger due to the size of the video files and code. This dataset is expected to be on the order of a few GB (1-5 GB) since there will be around 40-50 video files that are not too long in length (~10 seconds each).

## About the Author

The team thus far consists of Michael Pfeiffer. Michael is a Graduate Student Researcher in Robotics at OSU.
