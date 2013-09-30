protocol_viewer - a tool to help you prep mastermixes for PCRs and stuff...
===========================================================================

Description
-----------

protocol_viewer is a small command line tool written in Python that will help you keep track of your lab protocols and prepare mastermixes for any number of reactions.


Usage
-----

On an Unix command line just give the command 'protocol' followed by the reaction name and the amount of reactions you need the mastermix for.


Requirements
------------
Python 2.7.3


Examples
--------
```shell
Prepare a Phusion mastermix for three reactions
$ protocol phusion 3
>Phusion PCR 3X
>48.75 ul       water
>15.0 ul        5X HF
>1.5 ul         10 mM dNTP
>3.0 ul         10 uM forward primer
>3.0 ul         10 uM reverse primer
>0.75 ul        Phusion
>Divide 24.0 ul on 1.0 ul of template

Display all PCR protocols and calculate mastermixes for five reactions
$ protocol pcr 5
>Phusion PCR 5X
>81.25 ul       water
>25.0 ul        5X HF
>2.5 ul         10 mM dNTP
>5.0 ul         10 uM forward primer
>5.0 ul         10 uM reverse primer
>1.25 ul        Phusion
>Divide 24.0 ul on 1.0 ul of template
>
>EF-PCR (25 ul) 5X
>75.0 ul        water
>25.0 ul        5X Q5 buffer
>2.5 ul         10 mM dNTP
>1.5 ul         SYBR 1/500
>5.0 ul         10 uM forward primer
>5.0 ul         10 uM reverse primer
>1.0 ul         Q5 HotStart polymerase
>Divide 23.0 ul on 2.0 ul of template
>
>Emulsion PCR 5X
>150.0 ul       5X Q5 buffer
>15.0 ul        10 mM dNTP
>60.0 ul        0.5 uM forward primer
>60.0 ul        10 uM reverse primer
>375.0 ul       water
>15.0 ul        Q5 polymerase
>Divide 135.0 ul on 15.0 ul of template
