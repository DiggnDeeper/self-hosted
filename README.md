# self-hosted
Currently, using docker-compose to create an up-to-date, flexible array of secured web apps that anyone can run.

Join our Discord: https://discord.gg/Tf5rsbv

I (we) will try to create complete, easy to follow documentation and best practices here. To be clear, I am not a Docker expert or any other kind of expert. I'm just someone that wants this kind of thing to be available and I'm willing to do what I can to make that happen. 

Please feel free to jump in and help out and make it better.

# What is the reason for this project?
The push to self-host was rekindled because my host (Hostinger), like most hosts, don't allow file sharing, so I could not run NextCloud on their servers. So, I installed NextCloud on my server and then realized I wanted more copies of it running for clients and myself. To do that, I needed a reverse-proxy and certs for an SSL. The easiest way to do that is with Docker. Also, a new CRM I wanted to try out, Corteza is only available as a Docker image.

Messing with web-apps like NextCloud, WordPress, and CRMs is what I like to do, so now I can. Some new ones only come as Docker images, and they all are available or they can be Docker-ized.

Security is certainly increased, with the large caveat "if done right", because it is under my control. I view it as an opportunity to learn more about security.

It doesn't really add to decentralization, other than it is the easiest way to run some web-apps that I otherwise wouldn't have access to. Unfortunately, I still need domain names and that is a real centralized problem.

So, the tl:dr is I do it because it is the easiest and also most versatile way to try out and use stuff I wouldn't otherwise be able to and it is limited only by my hardware and connection.

# nginx reverse proxy with Let's Encrypt
This template comes from https://github.com/jwilder/nginx-proxy

This is the heart of the operation. It lets us point our domain name at our server and serve any number of other web-apps secured behind it.  


# NextCloud

# WordPress

# CRMs:
