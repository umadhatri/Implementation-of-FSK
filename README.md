## Implementation of FSK
This is the repository that holds the code for the implementation of the Frequency Shift Keying method of modulation of digital signals. This code was written in Python and only uses the simple NumPy and Matplotlib libraries.

## About FSK
Frequency Shift Keying (FSK) can be explained to a layman as a method of sending digital information using different pitches or musical tones. Imagine you have a musical instrument that can play two different notes: a low note and a high note.   
&ensp;&ensp;&ensp;&ensp;&ensp;Now, let's say you want to send a message using these two notes. In FSK, each note represents a specific binary value. For example, the low note could represent the number 0, and the high note could represent the number 1. To transmit your message, you would play a sequence of these notes, with each note corresponding to a digit in your message.   
&ensp;&ensp;&ensp;&ensp;&ensp;When someone receives these musical notes, they can listen to the sequence and decode the message based on the notes they hear. If they hear the low note, they know it represents a 0, and if they hear the high note, they know it represents a 1. By listening to the sequence of notes and translating them back into binary values, they can understand the original message.   
&ensp;&ensp;&ensp;&ensp;&ensp;FSK is like a musical language where different notes carry specific meanings. It's similar to Morse code, where different combinations of dots and dashes represent letters and words. Instead of using dots and dashes, FSK uses musical tones or pitches to convey information. One advantage of FSK is that it's robust against noise. Just like you can still recognize a familiar melody even if there's some background noise, FSK can handle interference or distortion in the communication channel and still deliver the intended message accurately.

## What does the code do?
It simply generates a random signal everytime you run it, converts it into digital data, generates an FSK signal for the binary data, and adds noise (random unwanted signals) to the FSK signal (to simulate the signal passing through a communication channel) and then demodulates it. It then computes the Fast Fourirer Transform of the demodulated signal so that we can look into the spectral aspects of the data that we have received.

## Why Python and not MATLAB?
Well, Python is free and open-source and has great libraries to use that can provide the same functionality as MATLAB.

## What is next for the project?
This was actually made as a part of my curriculum's end-semester project. Therefore, we (my teammates and I) feel that it is self-contained. I personally do not see a future for the project.
