Chemical-Balancer

Hello and welcome to my version of a python based Chemical equation balancer. this is mostly ment to be toutrial on how to install, and use for begginers not used to working with github, or most proggraming things. this will be a step by step guide on how to download, install, and use this program.
I will be moderatly updating this guide a the files in this Repo but it is not a priority.

Just a FYI this article is probably a lot better at actualy expaling how to install python properly on your machine:
  https://pythonprogramminglanguage.com/how-to-run/


Step 1:
  Step one is the easiest thing to do. Know what operating system you are on. that is it. Depending on that I will make two different tutorials(i am expecting that people on a linux machine already know all of this thus not needing a tutroial). Also for step one is to download the file, Depending on the operatin System you are usin chose the right file to dowload and use, for Mac systems the original normal Chemical-Balancer file is good, for Windows users download and use the MSChemical-Balancer file for Microsoft.
  
  

  <p>Depending on your Operating System go to the one guid that matches, <a href="https://github.com/TheArk99/chemical-Balancer#mac-os">Mac</a> is first <a href="https://github.com/TheArk99/chemical-Balancer/blob/main/README.md#windows">Windows</a> is at the bottom of the page, or you can click the link to bring you to them.</p>
  
<section>
 <h1>Mac OS:</h1>
 <p>Step 1:
      	step one for Mac os is to first pull up your terminal. You do this on macs simply by pressing the search button otherwords know as to Mac users as the spotlight button to locate apps. Then  to find the terminal simply type "terminal". It should show up as the first thing. if you want a more in depth how to check out this article on how to bring up your termianl.
        https://www.howtogeek.com/682770/how-to-open-the-terminal-on-a-mac</p>

 
 
<p>Step 2: 
      You need Python and pip(pythons download helper) installed on your Mac OS X system. 
			If you don’t have Python installed, open the Terminal app. 
			
Then install Xcode tools:

	xcode-select --install

Then isntall homebrew with this command:

	ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

Finaly to install Python on Mac by typing in your terminal:

	brew install python3

Now you need to install pythons helper installer, PIP To do this just type in your terminal:

	curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py

And then to install pip do this command:
	
	python3 get-pip.py

Check this site if you want to check if you installed pip correctly:
https://www.geeksforgeeks.org/how-to-install-pip-in-macos/
</p>

<p>Finaly the last step, Step 3:
			This last step is only needed for running my specific Chemical Balancer program, what you need to do is to use pip to install a few python libraries, Do note that if these libraries are not isntalled properly My program will not work.
			
To install the library needed for the program you need to install 'sympy' this is a libray for my program that my program relies on. In order to install this library for python you will need to use the termianl again.

To install the library simply type in the termianl:

	pip install sympy
	
That is it you just completly installed everything necacery to run my program, the last thing to do is to run the programn. You can do this by a few ways and i will leave a link to how to do all of them, but my prefered method of running these programs is by going back to the termianl, and typing this into the termianl:
	
	./<name of the program>
	
so to run my program you would do exactly:
	
	./Chemical-Balancer

If that does not work or run at all you can try going to the folder you are keeping the program, then in the termianl simply go to the folder by typing:
	
	cd /<the folders path>/
	
for example you could have the program in the downloads directory so you would type:

	cd Downloads/

Then once you are in that folder in the terminal you simply type:

	python Chemical-Balancer
	
This site is one that might help with hwo to run the program:
https://pythonprogramminglanguage.com/how-to-run/

that is it the program should run now and you should be able to figure out the rest once you are done with the program simply press the X to close the window or press <Ctrl + c> and then type 'exit' and hit enter.

 </section>
 <section>
<h1>Windows:</h1>
<p>This is the guid of how to install all the things on windows, keep in mind this is the hardest OS to do this on, I would highly recomend you use a unix based machine(Linux, Mac, BSD) instead of windows to run thisk, but that being said it still works, it is just a little harder to setup.

I am going to assume if you are using windows in 2021 that you are using a 64 bit OS, that being said that are other versions of python that i will not provied but will provide links to finding them. 

Step 1:
	Step one is to download python, you can do this through the link i am providing below:
	
64 bit Windows:

	https://www.python.org/ftp/python/3.9.2/python-3.9.2-amd64.exe
	
To download other versions of python you can go to their dowload site here:

	https://www.python.org/downloads/release/python-392/
	
Once that is downloaded go to the folder that you downloaded the installer for python just now and run it, go through the steps to install it. 

Here is a link that in more detail goes over the install of python for windows:

https://www.howtogeek.com/197947/how-to-install-python-on-windows/

Step 2:
	step two is to install and check that you have installed pip:
	
to install pip you will want to pull up the command line or powershell in windows, in windows 10 at least the shortcut to the command line is to press on you keyboard the <windows key + the R key> then type cmd, or you could press the start button and then type 'cmd'.

for earlier versions of windows here is a site telling how:

https://www.lifewire.com/how-to-open-command-prompt-2618089

Next to actualy install pip you will need to type in the prompt in the command line this:

	python get-pip.py
	
to see further see how to install pip for more information then you can go here:

https://www.liquidweb.com/kb/install-pip-windows/

Step 3:
	The last thing to install are the installing the python libraries:
	
to do this stay in the command line and then type:

	pip install sympy
	
That is it you have installed everything. Now to run the program:

Step 4:
	running the program:
	
There are many ways of running python programs in windows, the easiest way is to stay in the command line. Then you will want to navigate to where the programs file is located you can do this by typing cd just like in my Mac guide. although there are a few differences, if you have more than one hard drive and your file is in that ohter dirive then you will need to switch to that drive, to do this you will need to type the drives letter in the prompt of the command line. For example it will look somehting like this:

		Windows PowerShell
	Copyright (C) 2014 Microsoft Corporation. All rights reserved.
	
	PS C:\
	

IN order to swithch drives you need to typed the drives letter then hit enter for example, if i have two drives the main one named C and the other S and I want to go to drive S you just type S:

	Windows PowerShell
	Copyright (C) 2014 Microsoft Corporation. All rights reserved.
	
	PS C:\S
	
It should then change to that drive. However in order to get to the folder you are looking for in oreder to run the program you will want to be in the drive you need to be in then type 'cd', for example if you have your file in the dowloads folder you simply type:

	Windows PowerShell
	Copyright (C) 2014 Microsoft Corporation. All rights reserved.
	
	PS C:\cd Dowloads 
	
Then hit the enter or return key on your keyboard. If you need more help on how to change floders, paths, or dirves refer to this site:

https://www.sneppets.com/software/how-to-change-drive-and-the-directory-in-windows-powershell/

Now finaly to run the python program:
	
when you are finaly in the folder your program is in you simply will want to type 'python' then the the files name for example it should look like this:

	Windows PowerShell
	Copyright (C) 2014 Microsoft Corporation. All rights reserved.
	
	PS C:\Dowloads\python Chemical-Balancer
	
keep in mind you will need to have the files full and correct name this includes any '.', so if the name of the file was 'Chemical-Balancer.py' you would type this in the cmd prompt:

	python Chemical-Balancer.py
	
that is it the program should run now and you should be able to figure out the rest once you are done with the program simply press the X to close the window or press <Ctrl + c> and then type 'exit' and hit enter.

I hope this guide was helpfull. If you have and questions contact me at Noahfrmc@gmail.com
</p>
</section>
