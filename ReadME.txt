                                                 VEHICLE DETECTION USING OPENCV IN PYTHON





OVERVIEW:

     A vehicle counting and detecting system will be programmed. It will be sufficient to function for both still images and moving pictures. For the same, we'll be using OpenCV for carrying out all image processing operations and for detecting and counting cars and buses using a haar cascade classifier. However, you can also create your own haar cascade classifier.


SCOPE:

1. HELPS TRAFFIC POLICE:
     The traffic police may benefit from a vehicle detection and counting system because everything can be tracked from a single location, including how many vehicles have passed this toll and whose vehicle.

2. MAINTAINING RECORDS:
     Some people find it difficult to capture all the automobiles in their vicinity because they are passing by in real time. In order to get around this restriction, this application can be very well-versed to achieve the time-saving quality and be automated. It's not like one is viewing the video and they can pause it and take a note of it.

3. TRAFFIC SURVEILLANCE CONTROL:
     As this application can be planted anywhere as it only requires a camera or some wires (for establishing the connectivity with the central system) hence if the traffic is high at someplace, then from that area, an officer can monitor it and forward the information to next toll officer so that they could be prepared beforehand.

VEHICLE DETECTION:
     First, we use ABM to find potential vehicles. A common drawing is produced by this model using just a few training photos. Training photographs are taken from the top and front viewpoints because we only focus on automobiles with more than three wheels. In this view, many vehicles, vans, lorries, and buses have more comparable structures. When a vehicle is identified by our algorithm as a potential candidate, we isolate it within its bounding box and use the correlation value to determine whether or not it has mirror-like reflections.

VEHICLE COUNTING:
