# pulse_sensor_proteus_demo
Proteus simulation for pulse sensor interfacing with arduino.


1. Download the Arduino IDE and Install - https://www.arduino.cc/en/main/software

2. Download and Install Proteus software - https://crackdaily.com/proteus-download/

3. Extract the Zip folder Pulse_sensor_source_file

4. After Installing the Arduino IDE need to install the library for the heart beat sensor
	1. Got the Pulse_sensor_source_file folder and then open the Arduino Library folder copy the Timerone folder
	2. Go to the Document folder of your computer, open the arduino folder and then open library folder.
	3. Past the copied folder (Timerone)

5. Need to config the library files for arduino, heart beat sensor and LCD in proteus software
	1. Open the source location of the proteus software installed in your computer
	   in my case (C:\Program Files (x86)\Labcenter Electronics\Proteus 8 Professional\Library)
	2. Then open the Library folder in proteus software installed location 
	3. Before that copy the two file inside the --> Pulse_sensor_source_file/Proteus_library/Arduino/
	4. Past that copied files in the location mentioned in 1st point
	5. Follow the same procedure for other two folders in location mentioned in 2nd Point.

6. Basic installation and Library configs all are completed

7. Open the arduino source code from Pulse_sensor_source_file/Arduino Program/pulse_sensor.ino

8. Go to File->Perferences and checkIn compilation option, then click ok.

9. Then Click the Run button, Sketch->Verify/Complie or Ctrl+R or click the tick button on the top left corner below the file option.

10. Remaining procedures, please follow up the demo video.
