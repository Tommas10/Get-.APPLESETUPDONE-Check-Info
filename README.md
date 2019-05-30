# Get-.APPLESETUPDONE-Check-Info
This small shell script under macOS X.  Every time OS X starts, it checks to see if a file named .AppleSetupDone exists.  
This empty file is created after completing the Setup Assistant.  
It doesn't exist on a new out-of-the-box Mac, nor on a new Mac with OS X installed. 
By deleting this file, OS X assumes that the installation assistant has never run and starts it immediately after OS X starts.  
The Setup Assistant also runs with root privileges, which is why it can create a new user account with administrator privileges without any authorization. 

Open Macintosh HDD.
Go to this path: Macintosh HD ->var folder -> db folder -> .AppleSetupDone
