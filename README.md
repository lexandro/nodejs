# Dockerized Node.js
Dockerized Node.js image with bower based on minimal linux image Alpine

Usage:
=====
<<<<<<< HEAD
docker run -t lexandro/nodejs <command>

Bower is available with --allow-root option. Sorry, I'm beginner with linux. I'll update when I figured out how to avoid it :)
=======
docker run -it -v $(pwd):/work lexandro/nodejs sh

It maps your current folder into /work on the container
>>>>>>> cca73af59f5b391372b402e378f3e5134f29fdd8
