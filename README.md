Introduction
OctoDNS is an infrastructure-as-code tool that allows you to deploy and manage your DNS zones using standard software development principles, including version control, testing, and automated deployment. OctoDNS was created by GitHub and is written in Python.

Prerequisites
Before you begin this guide you’ll need the following:

One Ubuntu 18.04 server set up by following the Initial Server Setup with Ubuntu 18.04, including a sudo non-root user and enabled firewall to block non-essential ports. your-server-ipv4-address and your-server-ipv6-address refer to the IP addresses of the server where you’re hosting your website or domain.
A fully registered domain name with DNS hosted by a supported provider. This tutorial will use your-domain throughout and DigitalOcean as the service provider.
A DigitalOcean API key (Personal Access Token) with read and write permissions. To create one, visit How to Create a Personal Access Token.
Once you have these ready, log in to your server as your non-root user to begin.
