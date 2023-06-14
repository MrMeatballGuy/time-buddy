This script is ugly, but i got tired of calculating the amount of hours spent on features at work manually, which is necessary since the time tracking i use daily doesn't have a "from" and "to" mode, so i just needed something quick and dirty to make my life a bit easier.  

The first column of the input CSV is the start time, the second is the end time and the third is an identifier for the task.  
A simple row could be `08:00, 10:00, BAP-29`.  
Then after adding the directory of the executable file to $PATH it can simply be used like so: `tibu your-file-here.csv`  

I don't expect this script to be that useful to others, the only reason it's public is so i can grab it even if i happen to not be logged in for whatever reason.