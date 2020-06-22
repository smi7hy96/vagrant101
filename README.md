# Development Env and Vagrant 101

## Environments

### What is an Environment
An Environment is a place where code is run and stored.

### Dev Environment
The Developer Environment is where the developers write code, this will likely be on an individual's local machine.

### 4 Pillars

- Flexibility - Adapt to Changes quickly
- Ease of Use - Easy for developers to be able to use
- Robustness :-
  - 100% Uptime
  - Fast and Continuous Development
- Cost :-
  - Cap-ex & ops-ex
  - Infrastructure
  - Downtime
  - Slow Innovation

### Dev-ops Problems & Solutions
An issue that comes with the dev Environment is there are so many different variables that change between different developers machines. Whether that be OS, ram, browser, IDE version. Because of this, some code may work on some machines but not others which does not help if it was to be produced publicly.
Therefore, using a Virtual Machine (Such as VirtualBox) is a solution to this as developers can emulate a certain machine set up so that they are (almost) all running the code on exactly the same machine. This can be used for the testing Environment to ensure that the code works correctly before moving to the final production Environment.

## Vagrant & Virtual Box

### Vagrant
Vagrant is an OS software used to build and maintain virtual development Environments such as VirtualBox.
### Virtual Box
VirtualBox is an OS virtual machine software that can create virtual machines running various operating systems and emulate another machine

## NGINX
NGINX is a web server that can be used for web serving and also as a reverse proxy.
