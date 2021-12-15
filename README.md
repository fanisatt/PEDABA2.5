# PEDABA2.5
Data Base Maker

gcc -c prog_582.c -lSDL_bgi -lSDL2 -lSDL2_image

gcc -c input88.c -lSDL_bgi -lSDL2

gcc -o PEDABA2.5 prog_582.o input88.o -lSDL_bgi -lSDL2 -lm -lSDL2_image

Installation Instructions for Pedaba 2.5
Pedaba is a powerful portable general purpose database application for Linux 64bit Operating Systems (OSs).
Pedaba 2.5 is simply ... sexy !!
It is a special application for creating and managing databases ! It has many functions and it takes some time to learn and use it.
Pedaba combines texts, images, numbers, arithmetic, dates and general statistics to create databases NOT of general form but of your personal taste, which are stored in your hard drive and not in the clouds. It also has the ability to combine your data inside pedaba with several well-known Linux applications.
The application is written in pure C language.
It has been tested in modern Linux OSs (Mint 20.2 - Kubuntu 20 etc...)
Memory requirements range from 160 to 400 MB approximately.
It supports English and Greek languages. It is compatible with "us" - "uk" and "el/gr" keyboard  layouts.
As with most open source applications, the pedaba creator does not provide any warranty on application functionality or on your data security.
Use it at your own risk.
Before you try Pedaba 2.5 , perhaps you have to install some official packages pedaba needs. 
You must install  libsdl2-image-2.0-0  from your OS repositories - perhaps it is already installed.
Perhaps you have also to install "Zenity" or "Yad" (from your OS repositories - Pedaba will inform you if there is a real need to install any of them..).
Download and Decompress my Pedaba2_5.tar.gz file.
Then, simply copy the pedaba folder to your personal directory "/home/UserName". Please NOTE that the pedaba folder and the files inside it MUST be in your personal directory !
Within the "Pedaba" folder you will also see the executable file "PEDABA2.5-latest-x86_64.AppImage" . Please check and mark that it is executable ! Right-click the AppImage file and select Properties from the menu. Go to the Permissions tab and tick the Execute box to allow executing the file as a program. Close the Properties and click the AppImage to launch the program.

ATTENTION : For the MX Linux and other distros , the application image is not functional ! There is a simple solution :
You must install an SDL_bgi  library very easily , you can see the library  ("sdl_bgi_2.4.1-1_amd64.deb" and "SDL_bgi-2.4.1-1.x86_64.rpm") into the folder "Pedaba". Choose the Debian or the RPM package  according to your OS and install it.  
(For PCLINUX users only , please give as root : "rpm -ivh /pathname/SDL_bgi-2.4.1-1.x86_64.rpm").
Don't forget to install  libsdl2-image-2.0-0 too.
After this you can RUN the file "PEDABA2.5" (not the application image..) but, you probably have to make a permanent adjustment to run this file  with the custom command "sh -c" or "bash -c". (This file is the object C code,  NOT a script !)

Finally, to understand how pedaba works and take advantage of its features, open the file "Read_General_Instructions_English", take a look, get an overview at the beginning and as you use it you will see every detail. 

Many Thanks to Dr. GUIDO GONZATO who created a special SDL_bgi graphics compatibility library (Borland Graphics Interface - based on the well-known SDL 2) and gave me detailed instructions on how to incorporate his library with my C code to create the application image file !
Many thanks to the *xkblayout-state* creator ! It is a very smart application !
Many Thanks to all ... Linux workers...!!

Sincerely Yours
Fanis Attard
(email : fanisatt@yahoo.gr)
