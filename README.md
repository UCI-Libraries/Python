UCI Libraries

Tuesday February 26, 2019 & Thursday February 28, 2019

1:00 PM - 5:00 PM

Instructor(s): Danielle Kane

<b><a href="https://www.eventbrite.com/e/intro-to-unix-shell-tickets-53820982006">REGISTER HERE</a></b>

Please Note: You must be a UCI affiliate to register, please contact kaned@uci.edu if you are not a member of the UCI community to see if there is room before registering

**General Information:** The Unix shell has been around longer than most of its users have been alive. It has survived so long because it’s a power tool that allows people to do complex things with just a few keystrokes. More importantly, it helps them combine existing programs in new ways and automate repetitive tasks so they aren’t typing the same things over and over again. Use of the shell is fundamental to using a wide range of other powerful tools and computing resources (including “high-performance computing” supercomputers). These lessons will start you on a path towards using these resources effectively.

**Who:** The course is aimed at graduate students and other researchers, including undergrads, faculty, staff and community members. <b>You don't need to have any previous knowledge of the tools that will be presented at the workshop.</b> 

**Where:** Langson Library Rm 228. Get directions with <a href="https://www.openstreetmap.org/#map=17/33.64745/-117.83871">OpenStreetMap</a> or <a href="https://goo.gl/maps/528F8BGTYvJ2">Google Maps</a>.

**When:** January 31, 2019. <a target="_blank" href="https://calendar.google.com/event?action=TEMPLATE&amp;tmeid=Nmhkc2U0dHUzYmxnaWE5cmpydXRhYmYwNmUga2FuZWRAdWNpLmVkdQ&amp;tmsrc=kaned%40uci.edu"><img border="0" src="https://www.google.com/calendar/images/ext/gc_button1_en.gif">Add to your Google Calendar</a>.

**Requirements:** Participants must bring a laptop with a Mac, Linux, or Windows operating system (not a tablet, Chromebook, etc.) that they have administrative privileges on. They should have a few specific software packages installed (listed below). 

**Accessibility:** We are committed to making this workshop accessible to everybody. The workshop organisers have checked that:

    The room is wheelchair / scooter accessible.
    Accessible restrooms are available.

Materials will be provided in at the workshop and large-print handouts are available if needed by notifying the organizers in advance. If we can help making learning easier for you (e.g. sign-language interpreters, lactation facilities) please get in touch (using contact details below) and we will attempt to provide them.

**Contact:** Please email Danielle Kane at kaned@uci.edu for more information.

Syllabus: The Unix Shell

1. Using libraries
2. Working with arrays
3. Reading and plotting data
4. Creating and using functions
5. Loops and conditionals
6. Defensive programming
U7. sing Python from the command line
 
**Setup**

You will need access to the software described below. In addition, you will need an up-to-date web browser.

We maintain a list of common issues that occur during installation as a reference for instructors that may be useful on the Configuration Problems and Solutions wiki page.

**The Bash Shell**

Bash is a commonly-used shell that gives you the power to do simple tasks more quickly. <a href="https://gitforwindows.org">Download the Git for Windows installer</a>.

    Run the installer and follow the steps bellow:
        Click on "Next".
        Click on "Next".
        Keep "Use Git from the Windows Command Prompt" selected and click on "Next". If you forgot to do this programs that you need for the workshop will not work properly. If this happens rerun the installer and select the appropriate option.
        Click on "Next".
        Keep "Checkout Windows-style, commit Unix-style line endings" selected and click on "Next".
        Keep "Use Windows' default console window" selected and click on "Next".
        Click on "Install".
        Click on "Finish".
    If your "HOME" environment variable is not set (or you don't know what this is):
        Open command prompt (Open Start Menu then type cmd and press [Enter])
        Type the following line into the command prompt window exactly as shown:

        setx HOME "%USERPROFILE%"
        Press [Enter], you should see SUCCESS: Specified value was saved.
        Quit command prompt by typing exit then pressing [Enter]

This will provide you with both Git and Bash in the Git Bash program.

Mac OS X: The default shell in all versions of Mac OS X is Bash, so no need to install anything. You access Bash from the Terminal (found in /Applications/Utilities). See the Git installation video tutorial for an example on how to open the Terminal. You may want to keep Terminal in your dock for this workshop.

Linux: The default shell is usually Bash, but if your machine is set up differently you can run it by opening a terminal and typing bash. There is no need to install anything.


**Python**

Python is a popular language for research computing, and great for general-purpose programming as well. Installing all of its research packages individually can be a bit difficult, so we recommend Anaconda, an all-in-one installer.

<p>
  Regardless of how you choose to install it,
  <strong>please make sure you install Python version 3.x</strong>
  (e.g., 3.6 is fine).
</p>

<p>
  We will teach Python using the <a href="https://jupyter.org/">Jupyter notebook</a>,
  a programming environment that runs in a web browser. For this to work you will need a reasonably
  up-to-date browser. The current versions of the Chrome, Safari and
  Firefox browsers are all
  <a href="https://jupyter-notebook.readthedocs.io/en/stable/notebook.html#browser-compatibility">supported</a>
  (some older browsers, including Internet Explorer version 9
  and below, are not).
</p>

Windows
Video Tutorial: https://www.youtube.com/watch?v=xxQ0mzZ8UvA

    1. Open https://www.anaconda.com/download/#windows with your web browser.
    2. Download the Python 3 installer for Windows.
    3. Install Python 3 using all of the defaults for installation except make sure to check Make Anaconda the default Python.

macOS
Video Tutorial: https://www.youtube.com/watch?v=TcSAln46u9U

    1. Open https://www.anaconda.com/download/#macos with your web browser.
    2. Download the Python 3 installer for OS X.
    3. Install Python 3 using all of the defaults for installation.

Linux

    1. Open https://www.anaconda.com/download/#linux with your web browser.
    2. Download the Python 3 installer for Linux.
    (The installation requires using the shell. If you aren't comfortable doing the installation yourself stop here and request help at the workshop.)
    3. Open a terminal window.
    4. Type: bash Anaconda3-and then press tab. The name of the file you just downloaded should appear. If it does not, navigate to the folder where you downloaded the file, for example with: cd Downloads. Then, try again.
    5. Press enter. You will follow the text-only prompts. To move through the text, press the space key. Type yes and press enter to approve the license. Press enter to approve the default location for the files. Type yes and press enter to prepend Anaconda to your PATH (this makes the Anaconda distribution the default Python).
    6. Close the terminal window.
