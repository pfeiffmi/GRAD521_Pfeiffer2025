# 1. Data Description

## 1.1. Human Subjects Data

The first dataset will consist of all relevant human subject data. This includes demographic information (age, sex, race, home country), general attitudes towards robots, familiarity with robots, per-trial information (accuracy, confidence, reaction-time), and the overall task information (subjective task-load rating). All data will be stored in a spreadsheet alongside a corresponding subject ID and task version ID to match the subject and display to the data obtained. The data will be collected and saved to a spreadsheet as the user interacts with the computer software by manually entering the information or having it collected automatically throughout the experiment.

### 1.1.1. Dataset Size

The human subjects dataset is expected to be on the order of MB (100-999 MB) since we anticipate testing around 40 participants on about 60 trials alongside responses to questionnaires.

## 1.2. Metadata

The second dataset will consist of data for conducting the test (and available for replication of the study). This will be the metadata, which includes the code for displaying the interface, the recordings of the camera feed (as video files) and tactile feed (as spreadsheets) for each grasp, and the code for all analyses performed in the study. This data will be collected prior to the study by storing recorded sensory feeds from a robotic arm that is currently in the lab.

### 1.2.1. Dataset Size

The metadata dataset will be larger than the human subjects data due to the use of video files alongside code. This dataset is expected to be on the order of a few GB (1-9 GB) since there will be around 40-50 video files that are around 30 seconds each.

# 2. DMP Roles

The project will consist of three members: the principal investigator (PI), a software-focused graduate student (graduate student 1), and a hardware-focused graduate student (graduate student 2). These members will be split into the roles data management plan (DMP) roles as follows:

> Archiving and Preservation - ensure the data preserved and accessible over a long-term period
> > Members:
> > > PI
> 
> Data Manager - party responsible for overseeing aspects of the data generation, documentation, and sharing
> > Members:
> > > PI
> 
> Protection of Sensitive and Protected Data - ensure that sensitive and protected data is secure to follow all legal and ethical guidelines
> > Members:
> > > PI
> 
> Instrumentation Maintenance - ensure all instrumentation for data collection is working and calibrated
> > Members:
> > > Grad Student 2
> 
> Data Collection/Data Generation - run experiments to gather data
> > Members:
> > > Grad Student 1
> > > Grad Student 2
> 
> Data Organization - organize the data to follow a specified format/guideline
> > Members:
> > > Grad Student 1
> 
> Metadata Generation - gather metadata and ensure that the appropriate metadata standards are followed
> > Members:
> > > Grad Student 1
> > > 
> > > Grad Student 2
> 
> Quality Control - ensure data quality by testing, reviewing, and cleaning data
> > Members:
> > > Grad Student 1
> 
> Data Analysis - perform analysis on the data
> > Members:
> > > Grad Student 1
> 
> DMP Implementation - ensuring implementation of the DMP and the proper onboarding of new members
> > Members:
> > > PI
> 
>  Access Control - manage access of the data by authorizing users and managing higher-level access of team members
> > Members:
> > > PI
> 
> Software Creation and Maintenance - developer of the code and other relevant software
> > Members:
> > > Grad Student 1

In the event where someone with a data management responsibility leaves the project, then it will be the responsibility of the PI to remove any access that the person might have to the project and reassign the relevant roles to existing/new members of the team.

# 3. Formal Data Management Requirements

## 3.1. Department of Defense Requirements

Since the project is funded by the Office of Naval Research (ONR), then we can observe the specific data management requirements for projects funded under the Department of Defense (DOD) using DMPtool.org. These include:

> 1. Types of data produced
> 
> 2. Specifying data and metadata standards
> 
> 3. Conditions for accessing and sharing
> 
> 4. Conditions for reuse, redistribution, and creation of derivative works
> 
> 5. Plans for archiving and preservation
> 
> 6. Justification for the restriction of data

Point 1 was satisfied in section 1 above. As for point 2, 3, and 5, we can have our data be a part of a DSpace repository, which allows for open-access of our data with the ability to set metadata standards such as the Dublin Core standard. Last, for point 4, to allow for reuse of the data without worry, we would allow people to reuse and redistribute the data and metadata with very little restrictions by indicating a CC-BY license. Note, in regards to the restrictions of data on point 6, this will be explained in the human subjects requirements.

## 3.2. Human Subjects Requirements

In order to protect human subjects, we must ensure that data is anonymized. This goes beyond having random identifiers per subject since demographic information could potentially be used to identify a subject. For this reason, we will ensure that the identity of the human test subjects is protected by only sharing task relevant results and only providing a general statistic for the test subject sample regarding the demographics. Essentially, we will not match the demographic information to each test subject in the shared data.

# 4. Data Storage

Data will be stored on an online repository in two places: GitHub and DSpace. The data on a Github repository acts as a backup to ensure that data is saved while gathering data. However, the DSpace repository will be the formal repository where data will be uploaded and metadata will be formatted to a set standard.

# 5. Backup Strategy

To ensure that data is not lost, the backup strategy will consist of having data be stored locally as well as on two cloud servers (GitHub and DSpace). The local repository ensures that data can be accessed offline and the two cloud servers ensure that data can be recovered if the local machine is stolen or damaged, even if one of the two cloud servers is lost. Regarding data being transferred when graduating, this is accounted for by giving administrator access to the lab PI.
