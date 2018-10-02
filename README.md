Run

docker run -p 8080:80 sshenoy/portfolio

to run locally


Run

docker build . -t sshenoy/portfolio

to build any changes

To push to DPR

docker tag sshenoy/portfolio sds307/portfolio:v1
docker push sds0307/portfolio:v1


To rub from DPR

docker run -p 4000:80 sds0307/portfolio:v1