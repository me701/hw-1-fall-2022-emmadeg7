# ME 701 -- Homework 1 -- Emma Degenhardt

## Instructions

Your solution should be an update to this `README.md` file that will be
committed back to your repository created when you clicked the HW 1 link.

## Problem 1 -- Open-Source Software

### Statement

Think of the things you do routinely on a computer that require
specific software packages.  Find an
open-source solution from the software repository
for one of these activities and tell me about it in 100 words or less.
For example, I used to do lots of audio recording when I was in
high school (not *that* long ago) and used special (and
pretty expensive) tools like
Cakewalk Sonar.  Since then, I've found an
open-source package for doing multitrack
recording called Ardour that doesn't have all the bells and
whistles but, because I can program in C++ and the
source code is available, I could, in theory,
create any such whistles I need.  **Note**: You may not
describe anything already discussed in class (e.g., the LibreOffice suite
or Octave).

### Solution

I have had to use iMovie for class projects before, I found a free open-source alternative called OpenShot.
This is for those without Macs who did not have access to iMovie. In high school I did not have a Mac computer, 
so when I had to edit all of my video clips into one “movie” I had to go to my friend’s house to use her iMovie 
application. OpenShot has the ability to cut videos together, layer videos and sounds, add transitions, add text, 
and video editing. OpenShot has all of the basic functionality that iMovie does, making it a great alternative to 
me using my friend’s iMovie application.

## Problem 3 -- Your CPU

### Statement

Figure out how to display information about your CPU via the
command line.  This should include at least the **processor
speed** and the **number of cores**.  Describe your command(s) below.
(Hint: redirection is helpful; remember, that's like
using `ls > directory_contents.txt` to dump the contents of a directory to a file.

### Solution

To display CPU information on my Mac I used:
system_profiler | grep Processor

That command provided the following information:
   IOSlaveProcessor:
      Bundle ID: com.apple.driver.IOSlaveProcessor
      Location: /System/Library/Extensions/IOSlaveProcessor.kext
      Processor Name: Dual-Core Intel Core i5
      Processor Speed: 2.3 GHz
      Number of Processors: 1

## Problem 4 -- Resource Hogs

### Statement

Figure out how to list the programs that use the most
amount of (1) processing and (2) memory.  Describe your command(s)
in your writeup.

### Solution

To find how much memory and processing my applications are using I used the following command in my terminal:
top

## Problem 5 -- `bash`

### Statement

Where is `bash` located on your Linux system?  And what version of
`bash` are you using?  Make sure to provide any commands you use to
determine this information.

### Solution

My bash is located in /bin/bash. I found this by using the “which” command in my terminal.
The bash version I am using is 3.2.57(1)-release. I found this out by typing the following into the terminal:
Echo “${BASH_VERSION}”
