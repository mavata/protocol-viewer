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
```python
#Prepare a Phusion mastermix for three reactions
protocol phusion 3


#Display all PCR protocols and calculate mastermixes for five reactions
protocol pcr 5
