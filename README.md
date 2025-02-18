<p align="center">
  <img src="https://github.com/schizopup/Linux-Imaginary-iso/blob/main/images/logo_medium.png"/>
</p>

# Linux Imaginary 0.5.X (Sachiel)

### CURRENT VERSION 0.5.9

<h2>Currently working on the custom kernel, for now the kernel is linux zen</h2>

<br/>
This is my custom Arch based distro called Linux Imaginary, its still in development. This is version 0.5.X (Sachiel). This live iso comes with nmtui for easy access to the internet, as well as vim for any potential modification that must be made.
The real nice part about this puppy right here is the auto installer. All in CLI, you choose your user, your passwd, hostname, disk to format, you choose your DE / WM and it does all the rest of the job itself!
<br/>
<h3> Screenshots of the live iso and the end product at the end. </h3>

<br/>
<h2> What does Linux Imaginary offer? </h2>
Linux Imaginary offers a fast, easy, and lightweight way to install an Arch based distro, as well as custom repositories for the pacman package managers. It also comes prebundled with a small set of software to help with the first few parts of setting up your own linux machine. You dont have to use this distro if you know what youre doing with linux, this distro is for people who cant be asked to set up the first few steps of Arch linux themselves. Compared to other Arch linux based distros, Linux Imaginary does not install bloat, it tries to keep everything at a minimum while still giving you the tools to ease your way into Arch linux. Over time I plan on optimizing as much as I can both the live iso for faster install time as well as the system itself. As of writing this (Release 0.5.X Sachiel), this distro is still in its "beta" form, but keep yourself updated as I plan to constantly improve it.
<br/>
<br/>
<h2> Why did you do this?</h2>
This project was mainly to help myself learn better bash and the backend of how linux works. I have installed Arch manually many times but, and I have done LFS, but I wanted to test out if I could make an automatic install script for my own distro. The installer does borrow parts from ArchTitus due to it being used as my primary inspiration for this installer, so thank you to Chris Titus in a way. I dont expect this OS to gain any traction, its pretty much just a fun project for me also an auto installer cause i reinstall linux so much, so if anyone actually uses this, thank you.

<br/>
<br/>

### System info scripts other than neofetch are currently not natively supporting the distro ascii, however the file for the ascii can be found in your root directory post install

<br/>

## Every version so far is bundled with
>
>yazi
>
>neofetch
>
>xorg
>
>the proper drivers for your system
>
>kitty terminal
>
>firefox
>
>ly display manager
>
>vim
>
>w3m (in case youre on a server setup)

The other packages may change depending on DE / WM you choose as well as if you decided to have a minimal or full installation of the OS.

<br/>
<br/>

## current version message

>
>BSPWM auto install currently does NOT work, at least it doesnt when I try on my VM
>
>
>I am trying to find a way to also repackage hyfetch at this moment. Hyfetch locks people from repackaging it to stop right wing trolls from adding offensive flags, which i understand, but it also means that until i can find a way to repackage it with the current distro ascii, an alias needs to be made in my bash/zsh config.
>
>Currently also trying to optimize it. 0.5.6 is the first public build as some of my friends and classmates wanted to try the OS for themselves, but the OS is nowhere near complete, its still too close to Arch for me to truly call it my own, in either way its here and god knows its queer.
<br/>
<br/>

<h2> What needs to be changed</h2>

Adding the possibility to keep the old home partition

Fixing my custom rice on BSPWM auto install

Optimizing the system

Removing as much bloat as I can from the installer and the post install script

Making the installer itself faster
<br/>
<br/>

<p align="center">
  <h1 align="center">Screenshot of the live iso</h1>
  <br/>
  <img src="https://github.com/schizopup/Linux-Imaginary-iso/blob/main/images/screenshot1.png"/>
  <br/>
  <h1 align="center">Screenshot of the end product (using the budgie configuration during install) </h1>
  <img src="https://github.com/schizopup/Linux-Imaginary-iso/blob/main/images/screenshot2.png"/>
</p>
