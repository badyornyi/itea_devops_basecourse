Homework 1-1 Readme.

1. Install Docker (if it is not installed) on machine where project will run
2. Clone/Download this repo to machine where project will run
3. In CLI navigate to 'hw_01_1' dir
4. Run in CLI:
docker run -d --name test-nginx -p 80:80 -v $(pwd):/usr/share/nginx/html:ro nginx:latest
5. In browser navigate to localhost or 127,0.0.1
You'll see 'Hello world!' page, if nginx container started and runs successfully.
