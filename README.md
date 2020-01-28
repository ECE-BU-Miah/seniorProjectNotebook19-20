# seniorProjectNotebook19-20
## Tyler Kaschner,  Christopher Smagacz, Advisor: Dr. Suruz Miah


Notebook for senior project (2019-2020)



Kickoff meeting (Date: 9/13/2019)
---

Meeting minutes
Set up Github site and notebook
9:00-11:00 1:30-2:30 Tuesdays and Thurdsays lab time each week
Lab time is used for coding and hardware work.
We will share work equally.
Dr Miah will help us install Latex and IPE extensible drawing editor outside of formal meeting.
5 members in research group we can collaborate to learn latex.
research meeting every other friday from 12 to 1
Bibtech need to download for bibliography
For report template it will all be in latex
Dr Miah created a google drive folder for us with referenceable material.
Google drive is where bibliography, referenceable documents, and project documents
Our goal for this semester is to code the previous years projects, then next semester add our own elements

Action: Read Previous years final report from page 1 to pg 37 then prepare a presention based on that and appendix e pg 71 to 74 present on those pages as well. The presentation will be a 30 minute presentation.

(Date 9/15/2019)
---
Tyler took notes on pages 1-10 of previous years report

(Date 9/17/19) Tuesday Lab
---
Christopher and tyler worked on understanding last years project progress while working on setting up presentation for 9/20/19 senior project meeting.

(Date 9/19/20) Thursday Lab
---
Christopher and tyler spent half of lab time adding slides to the presentation for 9/20/19 and the other half of the lab finalizing resumes for the job fair taking place that current day.

(Date: 9/20/2019 @ 3:30 PM) Weekly Meeting
---
Tyler and Christopher presented there presentation today.
Dr. Miah shared with us previous years project documentation we are unable to download, delete, or copy an files only allowed to view.
The Things to do before next meeting:
Complete project statement in latex on overleaf,
we need to read areo user manual, and  
look into areo lab guide and implement experiment 4.
we left the meeting at 4:32 Pm

[Overleaf v2 tutorial1](https://www.youtube.com/watch?v=rLWT0z6yvrk)

[Overleaf v2 tutorial2](https://www.youtube.com/watch?v=JwXQb25cpqA)

(Date: 9/23/2019 )
---
Tyler and Chris read the user manual for the helecopters to perpare for working on lab 4 tommmrow.
We plan on working on the project proposal after we implement lab 4.

(Date: 9/24/19) Thursday Lab
---
Christopher and tyler both worked to get the simulink models needed for lab 4 done. We got the models 80% done the last thing we need to add is the Helecopter module's. We were unable to find out where they are located during the lab time. We left the lab around 10:50 am.

(Date: 9/25/19) Weekly Meeting
---
Tyler and Christopher have agreed to finish the project proposal today so that Dr. Miah has time to give us feedback. We finished at 6:31pm and are going to send it to Dr.Miah

(Date: 10/1/19) Tuesday Lab
---
During our lab time we designed our simulink diagram based on the reference file s_aero_2dof_lqr_control. We were slowed down by issues surrounding the installed Quarc files. The Quarc modules we needed to complete the s_aero_2dof_lqr_control model were not found in the current version of simulink we were working with, which was 2018.

![snip5](https://user-images.githubusercontent.com/48564969/66240967-88d23700-e6c3-11e9-8941-350aa78b5022.PNG)


The Drawing shown above shows our Simulink drawing s_aero_2dof_lqr_control model. We are using this drawing to find the control gain value K in our matlab script.
Figure 1

(Date: 10/3/19) Thursday Lab
---
During this lab time we edited and fixed our previously mentioned simulink diagram and we solved this issue by making all necessary edits in Matlab 2017a which has the Quarc software we needed to finish our drawings.

![snip6](https://user-images.githubusercontent.com/55299289/66241113-e8304700-e6c3-11e9-9729-a122336f19b8.PNG)
---
The Drawing shown above shows our simulink drawing named q_aero_2dof_lqr_control and it is used to enable the USB interface for us to connect to the Quanser Aero.
Figure 2

![snip1](https://user-images.githubusercontent.com/55299289/66241103-e23a6600-e6c3-11e9-87ed-7d812985fc70.PNG)
---
The Figure shown above shows the pitch position as the control system runs and how it changes pitch when in use.
Figure 3

![snip2](https://user-images.githubusercontent.com/55299289/66241100-e1a1cf80-e6c3-11e9-8e88-448ef9b7a156.PNG)
---
The Figure shown aboves shows the yaw position as the control system runs and how it changes when in use.
Figure 4

![snip3](https://user-images.githubusercontent.com/55299289/66241101-e1a1cf80-e6c3-11e9-9f5d-0f85874a156c.PNG)
---
The Figure shown above shows the voltage applied to the yaw motor as the simulink model runs and how the voltage needs to be applied.
Figure 5

![snip4](https://user-images.githubusercontent.com/55299289/66241102-e23a6600-e6c3-11e9-9b1c-6cf51addada0.PNG)

The Figure show above shows the voltage applied to the pitch motor as the simulink model runs and how the voltage is applied to the pitch motor in a live system.
Figure 6

(Date: 10/3/2019) Thursday Lab
---

After we finished the first simulink model and got it fully functional we began the secound simulink model based on the file q_aero_2dof_lqr_control. We got this similink model around 85% complete the last part we need to add is the Quarc mdoelules which we have not been able to find yet. 

(Date: 10/8/2019) Tuesday Lab
---
Today we worked on getting the State feedback Control Simulink model named q_aero_2dof_lqr_control we weren't ultimately able to get the simulink model to connect to the connected Quanser Aero, we believe the problem to be that in our current version of matlab we cannot open an older reference file's subsystem which has an integral part to connecting to the quanser aero, we talked with Dr. Miah and discuessed the possibility of emailing the previous year's senior project group that worked on this project to try and resolve this issue.

(Date: 10/9/2019) Weekly Meeting
---
In this meeting we discussed the trouble we ran into trying to get the state feedback lqr control and how we should remedy the situation. Dr. Miah told us to ultimately email the previous years group to ask for their assistance to find the source code we need to get previously mentioned lab functioning. Dr. Miah also asked us to look into the Quarc Quick Start Guide and get that functioning in tommorows lab instead of continuing to waste time on the current lab.

(Date: 10/10/2019) Thursday Lab
---
Today we completed the Quarc Quick Start Guide and managed to get the 2-dof helicopters moving and in the video labeled as 20191010_102427_1[1].mp4 we demonstrate the movement of the helicopters. The video is attached to the project above.
<video src="20191010_102427_1[1].mp4" width="320" height="200" controls preload></video>


(Date: 10/16/2019) Weekly Meeting
---
We first went over any progress we got done over break which was adding to the github descriptions of the screenshots we got from the simulink models. Dr. Miah wants us to work on fixing our Mathematical Model of 2-DOF helicopter document as soon as possible. Our task for our next lab time is to implemient the state feedback control lab and get the helicopters moving agian. 

(Date: 10/17/2019) Thursday Lab
---
Today we finally got the simulink model of state feedback control of 2-DOF LQR lab functioning and managed to get video of the Quanser Aero changing pitch and yaw at desired increments functioning in a live environment. We managed to get this done after the previous year's senior project group responded to our email telling us where a very helpful file was located.

(Date: 10/22/2019) Tuesday Lab
---
Today we worked on remaking the state feedback control of 2-DOF Helicopters using the LQR algorithm simulink model with our own parameters in place to better understand the USB interface connecting the computer to the Aero. We ran into some simulation and build errors slowing our progress and had to remedy those which took up most of our lab time unfortunately.

(Date: 10/23/2019) Weekly Meeting
---
We first discussed our progress from last week, which was mostly additions to our project report. We then discussed our plan for our lab time this week, Dr Miah wants us in lab to create the State feedback Control simulink model from scratch without copying any modules from previous referencable material. Dr Miah also wants us to add him to our finalized project report that is due on 10/24/2019 at 11:55 PM.

(Date: 10/24/2019) Thursday Lab
---
Today Tyler coded the simulink model named q_aero_2dof_lqr_control from scratch doing what Dr. Miah asked of us in the previous meeting. We also edited the gain and saturation parameters in the simulink model to alter the Aero's movement to better understand the way the device operates. In a meeting with Dr. Miah we discussed our learning goals moving forward and he mentioned that he wants us to ultimately re-code this lab from scratch without looking at old referenceable material. 

(Date: 10/31/19) Weekly Meeting
----
Today Dr. Miah had us meet in the lab. We first talked about our progress on understanding the stateFeedbackControl Simulink model. After Dr. Miah on a piece of paper went of some more math with us we learned about the desired state vector's. The Desired state vectors are made up of the pitch and yaw at desried point of the user along with the pitch and yaw rate of change being zero. We also learned more about the Overall Cost Function that includes both voltage and error calculations. The two important variables included in this equation is Q and R, Q coresponds to error while R is voltage. When making the Q bigger and the R value small we are able to get the best performance for the helicopter having the ammount of voltage used not take priority. If the R value was made bigger while the Q value is small the opposite effect will take place. The helicopter would attempt to get to the desired location using the least ammount of voltage it can not taking into account the performance in the process. Me and tyler showed Dr. Miah our files and simulink modles, Dr. Miah has requested us to work on organization after our meeting he did not like how unorganized our files were but did enjoy the progress we had made on operating the helicopter. Currently We have an overshoot problem in our code and this is our main problem to fix before we make more progress.


(Date: 11/20/19) Weekly Meeting
---

(Date: 11/21/19) Thursday Lab
---

(Date: 11/26/19) Tuesday Lab
---
Today Tyler and Christopher worked on having the LQI_USB_implementation simulink model run properly. We needed to change the Gain peramerters so that it could run correctly with out code. we had to take out the signal generators that we originally had in the model from last week on thursday. We wanted to see if we could change the gain block to a number and have the helicopter move to the desired state. If we could do this then adding the signal generators in later wont be to much of a hasle. After some time we were succesful on being able to run the model properly and change the angles to the desired states we entered. 

Kickoff meeting (Date: 1/24/2019)
---
This was the first meeting of the new semester. The objective of this meet was to set up the weekly meeting time that would be best for everyone as well as decide the 2 weekly lab times. Dr.Miah was happy with our work from last semester and spent some time giving us feedback to improve our work for this semester. We need to work on better organizing our docmentation for the lab work we do and keep the github update the github as much as possible. The next weekly meeting Dr.Miah has asked us to prepare a recap of what was done last semester and our plans for the lab work that will be done in the upcomming weeks. 
