# Progressive Web Apps - Sneak Peak
This source code is part of Maximilian Schwarzmüller's "Progressive Web Apps - Complete Guide" course.

# How to Use
You need Docker installed on your machine.

Open your command prompt or terminal and navigate into this project folder. There, run `docker run --rm -it -v $PWD:/app -w /app -u $(id -u):$(id -g) node:10.12.0 npm install` to install all required dependencies.

Finally, run `docker-compuse up` to start the development server and visit [localhost:3000](http://localhost:3000) to see the running application.
