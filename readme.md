This is a simple Flask webapp that can run inside a docker container.

# Build the image

	docker build -t <name> .

# Start the container
	
	docker run -p 8888:5000 <name>

This example is part of the tutorial on docker available [here][1].

[1]: http://prakhar.me/docker-curriculum/
