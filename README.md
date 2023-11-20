# Cognitive_Surveillance
Cognitive Surveillance system to detect for any malicious activity in real-time

Real-time monitoring of attention of an indivdidual, estimated by combining the positions of eye and head. 

After observing for any unattentive activity (individual looking away from camera) , alerts are sent through warning popups and email notifications (for the concerned authority)

Used different functions to obtain facial positons and warn accordingly as follows:

1. landmarks.py: Used to locate the facial landmarks using facemesh
2. eye_position.py: Extracts the positions of eye based on pixel count
3. head_position.py: Estimates angle of head rotation, using rodrigue's rotational formula
4. warnings_emails.py: Sends warning popups on the screen and alerts through email notificaitons (including snapshots of the individual)

main1.py consists of the main code which combines all the components and effectively serve as a surveillance system 

Libraries used: opencv, numpy, tkinter, smtplib, mediapipe, MIMEMultipart, MIMEText, MIMEBase, encoders, os 

Worked on Microsoft Visual Studio IDE (efficient result)



