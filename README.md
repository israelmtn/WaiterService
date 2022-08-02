# Waiter service.
Simple api to simulate a service timeout in tests enviroments. 

# With docker
docker push metanoia/waiterservice:1.0

# Test
http://localhost:{port}/wait?secs={number of seconds to wait}

# Example for wait a minute starting on port 4559 
http://localhost:4559/wait?seconds=60
