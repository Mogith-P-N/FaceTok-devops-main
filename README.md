# Intro to DevOps - Project Starter Code

# Goal
## Containerize two Flask web services and use Docker Compose to orchestrate them
### For our project, we will be containerizing two Flask apps, one generates a Random Quote, and the other service consumes this and displays it on a neat front end.
### Then we shall be using Docker Swarm to orchestrate the services to achieve our end goal. This exercise will help us understand a real-world use case of Docker and Docker Swarm better.


## Environment Setup - Things needed to run Project.

Install Docker Desktop from here  - https://docs.docker.com/desktop/. 
Choose the distribution of your choice but we will be using Windows.

## Ouput on the localhost:5001/get_quote 
Since our service 2 "quote-disp" fetches random quotes from the service 1 "quote-gen", which is running on separate containers. 

<img width="924" alt="image" src="https://github.com/Mogith-P-N/FaceTok-devops-main/assets/113936190/dbc0f323-c104-4f7c-8880-d98532a2eccc">
