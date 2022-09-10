# theme-changing-animation
Error detection and correction- Introduction
•Networks must be able to transfer data from one device to another with acceptable accuracy.
•For most applications, a system must guarantee that the data received are identical to the data transmitted.
•Any time data are transmitted from one node to the next, they can become corrupted in passage.
•Many factors can alter one or more bits of a message. Some applications require a mechanism for detecting and correcting errors.
•Some applications can tolerate a small level of error.
•For example, random errors in audio or video transmissions may be tolerable, but when we transfer text, we expect a very high level of accuracy.
Loading…
Types of error
•Whenever bits flow from one point to another, they are subject to unpredictable changes because of interference.
•This interference can change the shape of the signal.
•In a single-bit error, a 0 is changed to a 1 or a 1 to a 0.
•In a burst error, multiple bits are changed.
•Based on the number of bit error, types of error are divided into two types
•Single bit error.
•Burst Error.
 
Single bit error
 

Note
Loading…
Burst error
 

A burst error means that 2 or more bits in the data unit have changed.

Note

Redundancy
•The central concept in detecting or correcting errors is redundancy.
•To be able to detect or correct errors, we need to send some extra bits with our data.
•These redundant bits are added by the sender and removed by the receiver.
•Their presence allows the receiver to detect or correct corrupted bits.
 

Detection Versus Correction
•The correction of errors is more difficult than the detection.
•In error detection, we are looking only to see if any error has occurred.
•In error correction, we need to know the exact number of bits that are corrupted and more importantly, their location in the message.
•The number of the errors and the size of the message are important factors.
 
Forward Error Correction Versus Retransmission
•There are two main methods of error correction.
•Forward error correction is the process in which the receiver tries to guess the message by using redundant bits.
•This is efficient, if the number of bits are small.
•Correction by retransmission is a technique in which the receiver detects the occurrence of an error and asks the sender to resend the message.
•Resending is repeated until a message arrives that the receiver believes is error-free (usually, not all errors can be detected).
Redundancy- Coding
 
