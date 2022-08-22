# introduction-to-distributed-technologies
Course Introduction to distributed technologies by FICT ITMO
For local deploy in docker container
```
git clone https://github.com/itmo-ict-faculty/introduction-to-distributed-technologies
cd introduction-to-distributed-technologies
docker pull squidfunk/mkdocs-material
docker run --rm -it -p 8000:8000 -v ${PWD}:/docs squidfunk/mkdocs-material
```