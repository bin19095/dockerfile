<b>#How to run the file?</b></br>
--download the file.</br>
--make sure you have node, docker and redis server installed.</br>
--Now, run "docker-compose up --build" this cmd will create and run the image in your local machine.</br>
(Meanwhile, it will create three images visit_redis_server, node_app, and network_default will create connection between the first two images.</br>
--Everytime the application is refreshed the visit_count will increase by 1 starting with 0</br>
--<b>We are not yet done!</b> in order to stop the images run cmd "docker-compose down" else, it will continue to occupy the memory in your machine < until it's 
terminated.

