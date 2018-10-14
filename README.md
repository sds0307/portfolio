Run

    docker run -p 8080:80 sshenoy/portfolio

to run locally


Run

    docker build . -t sshenoy/portfolio

to build any changes

To push to DPR

    docker tag sshenoy/portfolio sds307/portfolio:v1
    docker push sds0307/portfolio:v1


To run from DPR

    docker run -d --name portfolio -p 4000:80 sds0307/portfolio:v1

To check all containers

    docker container ls

To stop the container

    docker stop portfolio


Next steps
- How to deploy changes manually
- Script to deploy changes
- Circle CI set up
- Circle CI for deployments
- Get Domain and SSL
- Set up DNS to route Domain to IP
- Set up Linting
- Set up Unit Tests
- Set up Automated Tests

