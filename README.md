* Build
   - `sudo docker build .`
   - This builds an image
* Run
   - `sudo docker run -p 3000:3000 [id]`
   - Then runs a container based on the above image
* List all running containers
   - `docker ps`
* Stop running container
   - `docker stop [name]`
* While running visit `localhost:3000`
* To prune images
   - `docker image prune -a`
