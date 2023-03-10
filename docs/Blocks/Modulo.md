Outputs the remainder of a division calculation.

[[uploads/Modulo.png]]

Inputs:

* A: The value to be divided.
* B: Value to divide A by.

Output:

* Mod: The remainder of the division calculation A/B.

## Notes
* If the calculation doesn't have a remainder, the Modulo will be **0**.

## Examples
    Division:

    5 / 2 = 2.5
    10 / 5 = 2

    Modulo:

    5 % 2 = 1
    10 % 5 = 0

Uses:

* Do every X frames:
    * With the accompany of the [[Blocks/Current Frame]] block in input A, you can specify an event that takes places every X frames. For example, because 60 frames is 1 second, input B can be 60, and if the modulo is equal to 0, your event will be executed every 1 second.
    
    [[/uploads/com.martinmagni.fancade_Screenshot_2021.02.06_17.51.19.png]]
    _Image source:_ [[Script/How do I execute a script every second?]]
