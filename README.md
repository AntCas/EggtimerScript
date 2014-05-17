To Run: Download files and place in bin directory, make sure Path variable is set to look in bin 

~ echo $PATH

~ eggtimer 10 --> opens e.ggtimer.com/10min

~ eggtimer
Enter Time: 10 --> opens e.ggtimer.com/10min

eggtimer command will only accept positive integers

Make sure to edit the path to eggtimerx to be accurate on your system.

The command is split into two files inorder to catch a firefox error when opening a page from outside the firefox app. The Code from eggtimerx can be moved to eggtimer if you would rather see the error. There was no solution available on the internet with the official response from firefox being it was not an error they would be able to fix.
