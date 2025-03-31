Assignment to deploy a simple microservice using Github Actions.
to launch docker container with runner use command:docker run -d --name github-runner github-runner
to mount docker socket use command: docker run -d --name github-runner -v /var/run/docker.sock:/var/run/docker.sock github-runner