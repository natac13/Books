# Calculation for a Single Motor Feed

### Step 1 - Gather Initial Data
* Determine the **Full Load Amps(FLA)** from the nameplate on the motor frame or  from Table 44 and 45, 3-phase and single phase motors, respectively, using the *horsepower(HP)* and *voltage(V)* of the motor.
* Determine the **Duty Cycle** of the motor from the nameplate. If unavailable assume *continuous duty service*. 
* Determine the **Class** of motor form the nameplate, and **Enclosure Type**

### Step 2 - Conductor
* Minimum Ampacity - **28-106**
  - *Continuous Duty Service* not less than 125% of the FLA - **28-106(1)**
    + $$ConductorAmapcity \ge 1.25 * FLA$$ 
  - *Non-Continuous Duty Service* not less than the percentage from Table 27, which corresponds to the **Duty Cycle** of the motor, multiplied by the FLA of the motor. - **28-106(2)**
    + $$ConductorAmpacity \ge Table27Value * FLA$$
* Insulation Temperature Rating - **28-104**
  - Referring to the conductors which terminate at the motor box, the insulation rating needs to be that required by Table 37, based off the **Class** of the motor, unless marked otherwise. - **28-104(1) - first half**
  - Where ambient temperature exceeds 30$$^\circ$$C the conductor insulation rating needs to be increased by the difference between the ambient temperature and 30$$^\circ$$C, at a minimum. Therefore round up to select a purchasable conductor insulation. - **28-104(3)**
* Conductor Size Selection
  - Using the **Minimum Ampacity** calculated above, find the conductor size using Table 1, 2, 3 or 4 based off the method of conductor installation and type, and the *75$$^\circ$$ column*, except for Class A motor, which can based the size selection off the *90$$^\circ$$ column* - **28-104(1) - second half**

