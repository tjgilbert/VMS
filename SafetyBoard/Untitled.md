# Safety Board
PCB that has control over several parts of the AIR interlock circuit
* **BSPD**(brake system plausability device)
 * If the brake is pressed, and the motor is making more than 5kW of power, the BSPD must Open the AIRs and shut the car down.
  * The BSPD must latch on a fault and not be able to be reset by the driver  (reset behind the driver)
  * An indicator on the dash should indicate a BSPD fault.
* **IMD**(insulation monitoring device)
 * If the IMD detects a fault, the system must shut the car down must Open the AIRs and shut the car down.
 * The IMD must latch on a fault and not be able to be reset by the driver (reset behind the driver)
 * An indicator on the dash should indicate a IMD fault.
* **AMS**(accumulator management system)
 * If the AMS detects a fault, the system must shut the car down must Open the AIRs and shut the car down.
 * The AMS must latch on a fault and not be able to be reset by the driver (reset behind the driver)
 * An indicator on the dash should indicate a AMS fault.
                
