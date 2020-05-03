## How to run the container:

1. Once Docker is installed on your machine, in the root directory run `docker build -t sinatra_demo .`, where `sinatra_demo` is your chosen name for the container.
2. Then run `docker run -p 4567:4567 sinatra_demo` where the port numbers are the exposed port from the container and also the port where the app is accessible.
3. If the app is running, then run `curl localhost:/4567/hello-world` - You should get `{"message":"Hello Codeclan!"}` as a response!
