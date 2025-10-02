# Intro: : Quick Hydration for Temporary VDI Workspaces

As a Cloud Consultant, you often need to access client environments to perform your project's objectives. 
How you access these environments is at your clients' discretions. Some might a laptop, a thin client, a Chromebook, or even a Smart Card. 
The majority will offer a (Windows-based) Virtual Desktop that complies with the clients' security needs.

Given the option, the Virtual Desktop is often the optimal choice when working remotely within the client's environment.
You get first-hand experience with the clients' standards, SOPs, and their support services.

However, you're still responsible to perform the job you need, and you rely on several tools to do them. 
One option is to work with the client support team to have these tools installed, but it's almost never optimal. 
You can try to install these tools yourself, but you don't always have the luxury of the elevated privileges to do so.

That's what this _gist_ is for - a playbook of instructions to install your most commonly used tools in an ephemoral Windows Desktop Environment.
Even if they reset your user profile daily, or have to start over every time you log in, you're already armed with a library of instructions to quickly hydrate your virtual desktop and get to work.

**The goal is to minimize friction and cognitive load. Save that energy for the real job you're getting paid for.**

## Requirements
It's assumed that even if you don't have administrative privileges to the virtual Windows Desktop you're remotely accessing, you will have default privileges on your user profile, even if you lose that profile every time you log off.
* Access to a Terminal window
* Powershell 5.x and above

## Installation
