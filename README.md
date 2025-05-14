🎯 Hackademic CTF Platform

A CTF platform built using CTFd, preloaded with custom challenges across various categories. Clone, run, and start hacking!

Quick Start (with Docker)

Clone this repository:

git clone https://github.com/lucky-hacks/Hackademic-CTF.git 

cd MyCTF

Copy the environment file template:

cp .env.example .env

Start the platform:

docker-compose up -d

Access the platform in your browser:
URL: http://localhost:8000

Features

Preloaded challenges across multiple categories
Fully functional admin interface to manage challenges
Dockerized environment — no local setup hassle
Ready for self-hosted or team-based CTFs

Admin Login

After setup, log in using:

Username: admin

Password: admin
You can reset it using the CTFd admin interface.

License
MIT License — feel free to use, remix, and build your own CTF!

Credits
Built on top of the open-source CTFd platform.
Custom challenges and structure by Laxman Prajapati.
