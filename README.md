# EMG-Arm-project
To Develop a 3D Printed Myoelectric Prosthetic Arm or Robotic Arm to Control Hand Movements.

The controlling of prosthetic arm is based on Electromyography sensor module, which is controlled by another hand by wearing the band.
Step-1: Electromyography sensor (EMG) is connected to dry electrode and further, the dry electrode is attached to bicep muscle.
Step-2: EMG sensor will detect the moment of the muscle and produce some reference value depending on the EMG signal received on the sensor.
Step-3: the produced reference value if filtered and amplified, then amplified signal is fed to microcontroller.
Step-4: The microcontroller uses the Second order Digital IIR Butterworth Band-Pass filter, which produces frequency and envelop value.
Step-5: Using the envelop value servo rotation is given. Rotation signal is given for 6 different servo motor are used wrist moment and fingers moment of prosthetic arm.
Step-6: servo motor will rotate at angle of 90º and these servo motors are connected to the fingers of prosthetic arm using the fishing wires.
Step-7: servo angle calculations, Taking Calculations of Folding and Relaxing Hand, Let say Folding hand is 20 and Relaxing hand is 10, Then the difference between both Results is 10.
