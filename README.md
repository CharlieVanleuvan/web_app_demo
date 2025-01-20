# web_app_demo
This is a demonstration of creating a local webapp in a docker container

## Setup
Clone this repo to your local machine and use the following command (executed in the repo directory) to 
build the container from the `Dockerfile`.
```bash
docker build -t webapp-demo
```

Once that is complete, you can run the container with the following command:
```bash
docker run -p 8000:8000 webapp-demo
```

Then, navigate to [http://0.0.0.0:8000](http://0.0.0.0:8000) to view the webapp.