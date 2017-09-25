# BLDC-Brake-Circuit

--------

A kicad PCB design for Brake circuit for BLDC hub motor

-----------

** Component **

------------

* IC555
* Mosfet -IRF3710
* Opam LM321
* Voltage Regulator

** Purpose **

-------

As per my experience with BLDC HUB motors, most of the motor drivers apply brakes just by cutting off the power supply of the motor without any retarding force. The retarding force gets applied only all all three terminals of motor are connected together. So I designed a circuit which short circuits all three terminals of the motor after brake signal is applied with a small delay produced by IC555.

-------

** RISK **
-----
** WE NEED TO TAKE CARE THAT THE SOFT BRAKES ARE APPLIED BEFORE TO ENSURE THERE IS NOT SUPPLY AT MOTOR PHASE PINS **
