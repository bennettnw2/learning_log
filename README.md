# learning_log
### This is the learning log program from the book, "Python Crash Course 2nd Edition".
I have a working application and I am now working on containerizing and deploying to a Kubernetes cluster. I also created the Dockerfile to create a container.

### Instructions to create and run the container.
You will need git, python3, and docker installed on your computer.

* `git clone https://github.com/bennettnw2/learning_log.git`
* `cd learning_log`
* `python3 manage.py migrate`
* `docker build --tag learning_log`
* `docker run -p 8000:8000 learning_log`

Navigate to your localhost at port 8000 and you will have the containerized application running on your local computer. Feel free to take the containterized app for a spin. Next step, is deploying this container to a Kubernetes cluster.
