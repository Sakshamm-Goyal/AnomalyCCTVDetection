## Demo of Website :- https://saurabhpandey9752.github.io/Map/

# PPT : https://docs.google.com/presentation/d/185uYVznBI6WaFx-DnTIG2jB4sImjJndM/edit?usp=sharing&ouid=115371392160541994484&rtpof=true&sd=true
# Nirakshak - Geo Tagging and Video Analysis for Enhanced Public Safety

Welcome to Nirakshak, a web interface online portal designed to revolutionize the geo-tagging of CCTV cameras. Our platform aims to streamline the work of law enforcement agencies by providing clear and accessible information on private and public cameras, thus reducing the burden on investigations.

## Problem Statement

System for geotagging of privately owned Cameras - Private cameras in businesses, homes, and institutions play a crucial role in enhancing public safety and crime detection. Many private cameras lack clear locations, making it difficult for the police to efficiently access relevant video footage during investigations in specific crime-prone areas.

## Our Solution

### Geotagging:

To facilitate geotagging, we've developed a user registration form requiring personal details such as Name, Phone No., and Email ID. For camera information, users input the IP address and camera model. Additionally, we seek the user's consent to provide camera access. The platform offers law enforcement a comprehensive map view, distinguishing private and public cameras. Clicking on a camera point reveals detailed information about the camera and its owner from the database, along with the nearest police chowki.

### Live Alerts and Detections:

Our platform employs Yolov8 for analyzing large video streams, identifying over 80 distinct objects. A custom-trained model detects Violence/Fight, Guns, and Knives, triggering an alert (a beep sound) upon detection. OpenCV is utilized for License Plate detection, reading text using easy-ocr.


https://github.com/Sakshamm-Goyal/AnomalyCCTVDetection/assets/144555727/d1dd3d78-91b5-4415-a70e-63dc5cc2ab03



https://github.com/Sakshamm-Goyal/AnomalyCCTVDetection/assets/144555727/4396e98c-26c5-4ee6-bee2-fd435181e016



### Camera Safety:

An algorithm captures an initial picture from the CCTV, stored in the database. This image is periodically compared with live footage, generating a similarity score. If the score falls below the threshold, an alert notifies of potential issues with the camera, aiding in identifying displacements or obstructions.

https://github.com/Sakshamm-Goyal/AnomalyCCTVDetection/assets/144555727/5bdaaecb-3966-40cd-aa9f-f859282b8ab1


## Future Scope

1. *Path Tracking for License Plates:*
   Introduce an algorithm to track specific license plates, plotting their paths. This feature will enhance law enforcement capabilities by providing insights into potential routes a vehicle may take.

2. *Face Detection on CCTV Footage:*
   Implement a Face Detection algorithm to alert law enforcement when a wanted/criminal individual is spotted in CCTV footage.

This comprehensive solution not only addresses current challenges but also outlines a roadmap for future enhancements, ensuring Nirakshak remains at the forefront of technology for public safety.

https://github.com/Sakshamm-Goyal/AnomalyCCTVDetection/assets/144555727/9e247322-42bc-47c7-9871-dd1ad2628d98

https://github.com/Sakshamm-Goyal/AnomalyCCTVDetection/assets/144555727/fd49eb53-218b-45c2-ae3a-e3f2b01c7e1a

### Built With

- [Python]
- [MySQL]
- [Js]
- [HTML/CSS/BOOTSTRAP]
- [Ultralytics]
- [YoloV8]
- [django]
- [Tensorflow]

