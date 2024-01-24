In this Project, you will play with threads to play a musical tone. You are provided with music tone files and sample Java code that plays those music tones. The music tones correspond to the musical “do, re, mi fa, sol, la, si, do-octave”.

Your Task:

Write a Multi-threaded Java application with two threads to play the provided tones as follows:

Thread 1 will play do, mi, sol, si, do-octave.

Thread 2 will play re, fa, la, do-octave.

Notice that you have to synchronize the two threads so that the user will hear do, re, mi, fa, sol, la, si, do-octave in the right sequence. Also, the do-octave tone should be played with the two threads at the same time.

Bonus (3 points): Twinkle Twinkle Little Star

Extend your code to allow the user to play the song Twinkle Twinkle Little Start. The music tone for this song is as follows:

do do so| so| la la so| fa fa mi mi re re do
so| so| fa fa mi mi re so| so| fa fa mi mi re
do do so| so| la la so| fa fa mi mi re re do

The two threads must coordinate to play the music tone. Thread 1 can only play do, mi, sol, si, do-octave. Similarly, thread 2 can only play re, fa, la, do-octave.

Submission Instructions:

Submit all code and screen captures of sample runs.
Submit by the deadline, late submissions are not accepted
Resources needed for this assignment: https://www.dropbox.com/s/jvy2k62ahex0ze5/Multithreading%20%20Resources.zip?dl=0
