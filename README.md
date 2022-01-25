## Description of Application

Using Docker Compose to manage multiple containers running nginx, we can provide a simple proof of concept that can load balance and be scaled up.

NOTE: You will have to edit the nginx.conf file, docker-compose.yml file, AND the individual html files with each server/page you intend to host and load balance. You may also want to switch to a different balancing method depending on your traffic (i.e round robin, weighted round robin, etc.) TL;DR **IF YOU WANT TO LOAD BALANCE ACROSS MORE THAN 10 INSTANCES AND SCALE RELIABLY, CONSIDER IMPLEMENTING THIS APPLICATION WITH DOCKER SWARM OR KUBERNETES**

## Usage

Clone the repo using git:

 `git clone [URL HERE]`

Navigate to the `docker-challenge` directory

Run `docker compose up -d` in the `docker-challenge` directory to start hosting!


 






