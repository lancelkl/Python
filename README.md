# Python
split large file (GB) to smaller ones

Designed to handle large log file (1~2GB) from optical disc inspection machine. At first stage, I split the large file into small ones (just as large as EXCEL can process), then load them by EXCEL and calculate values that I needed. However, it's slow and troublesome to calculate by EXCEL. The second approach, I use Python to do all the calculation, then save the results into .txt file. Then EXCEL is used to load values and making graphs. It's far more fast and easy using Python to handle the irregular output in the log file. Around 2GB log file had been tested OK.
