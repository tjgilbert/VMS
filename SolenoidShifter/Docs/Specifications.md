#Solenoid Shifter Project
###Purpose:
To control and actuate a push/pull solenoid for shifting an FSAE combustion car.
###Specifications:
The controller **must:**
* Have two channels/outputs (push / pull)
* Have two inputs
* Be able to supply 40A of current at 12V
* Have an adjustable/programmable dwell (on) time
* Prevent actuating both outputs at the same time
* Be < 12V tolerant on all inputs
* Operate on 5-15 volts supply

The controller **should:**
* Have field programmable dwell time adjustmant (ie. DIP switches, knob.. etc)
  - over a certain range ie. 10-400ms
  - the delay should be repeatable / readable
* Have an output for throttle cut

The controller **may:**
* Have seperate dwell time adjustment for up / down shift
* Have CAN interface
* Have a gear indicator?
