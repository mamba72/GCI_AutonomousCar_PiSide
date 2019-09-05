# GCI_AutonomousCar_PiSide
This will be the code for the raspberry pi part of our autonomous car.
This program is designed to be placed on a Raspberry Pi.
It's purpose is to send a live camera feed to the server over websockets,
wait for the server to analyze the image and send back instructions of what to do next,
then drive based off the information recieved from the server.