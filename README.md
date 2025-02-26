# Python Counter Service App

![python-app-ezgif com-webp-to-jpg-converter](https://github.com/user-attachments/assets/ceb9266a-ba5e-4c70-9310-41203b482987)


The repo for the counter service Python app.

Python service called "counter-service."

It maintains a web page with a counter for the number of POST requests it has served and return it for every GET request it gets.

--------------------------------------------------------------------
Detailed pipeline overview here: [Medium](https://medium.com/devops-technical-notes-and-manuals/devops-example-project-for-your-resume-198e34d874b4).

---------------------------------------------------------------------
### Building and running your application

When you're ready, start your application by running:
`docker compose up --build`.

Your application will be available at http://localhost:8080.

### Deploying your application to the cloud

First, build your image, e.g.: `docker build -t myapp .`.
If your cloud uses a different CPU architecture than your development
machine (e.g., you are on a Mac M1 and your cloud provider is amd64),
you'll want to build the image for that platform, e.g.:
`docker build --platform=linux/amd64 -t myapp .`.

Then, push it to your registry, e.g. `docker push myregistry.com/myapp`.

Consult Docker's [getting started](https://docs.docker.com/go/get-started-sharing/)
docs for more detail on building and pushing.

### References
* [Docker's Python guide](https://docs.docker.com/language/python/)
