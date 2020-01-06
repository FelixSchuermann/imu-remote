# imu-remote
ThreeJS+RaspberryPi+IMU+websocketd project that lets you use a imu sensor for drawing/pointing to a screen

You can use websocketD to start an instance of your signal processing script. The Websocket takes in Data as JSON. You can modify your script to output the data in the shape of:

(c++):

cout << "{" << "\"accfx\":"<< OutputAcc_x <<",\"accfy\":"<< OutputAcc_y <<",\"accfz\":"<< OutputAcc_z << ",\"CFangleX\":"<< CFangleX << ",\"CFangleY\":"<< CFangleY << ",\"AngleZ\":"<< AngleZ << ",\"button\":"<< button <<"}"<< endl;

My signal processing Script will follow at some point. There is also a PDF in german that is describing the project.
