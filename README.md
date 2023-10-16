# Error-detection-and-correction
Using CRC and 7-bit hamming code



CRC-
Program generates codeword for given input digital data stream by performing CRC on each dataword using standard CRC-8.  Once codeword is formed, no.of hops and crossover probability is set by the user .Receiver decodes  the codeword to check if its corrupted or not. If error is detected, a message“discard”is  returned , else dataword is extracted from the codeword received.

7-BIT-HAMMING -
Program generates codeword for given input digital data stream by performing 7-bit hamming using even parity, on each dataword .  Once codeword is formed, receiver decodes  the codeword to check if its corrupted or not. If one error is detected, its location  is  returned and dataword is extracted from the codeword received.


Language used:  C++;

Libraries used:
1)#include<iostream>.
2)#include<vector>
           

Assumptions considered:
1)We are using even parity for 7-bit hamming

References:
Youtube  and  geeks for geeks.

How to run the code:
1)Create project.
2)Write the code.
4)Compile and run.

