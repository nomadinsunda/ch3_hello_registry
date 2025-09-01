```
git clone https://github.com/nomadinsunda/ch3_hello_registry.git
cd ch3_hello_registry

docker login
docker build -t docker.io/intheeast0305/ch3_hello_registry:latest .
docker push docker.io/intheeast0305/ch3_hello_registry:latest
```
