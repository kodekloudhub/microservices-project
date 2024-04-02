Project Overview
----------------

This project is a Python microservice written using Flask. It features a modular structure with separated folders for application logic, configuration, static files, and templates.

Installation
------------

1.  Clone the repository:

Bash

```
git clone https://github.com/your-username/microservices-project.git

```

2.  Install dependencies:

Bash

```
pip install -r requirements.txt

```

Usage
-----

Start the development server:

Bash

```
python app.py

```

Access the application at http://localhost:5000/.

Development
-----------

Here are some useful commands for development:

-   Start development server: `python app.py`

-   Run tests: `pytest`

-   Generate test coverage report: `make coverage`


Docker Build steps
-----------------
1.  Build the Docker Image: Navigate to the directory containing the Dockerfile and run the command `docker build -t your-image-name:tag .`. Replace `your-image-name:tag` with the desired name and tag for your image.

2.  Run the Docker Container: After building the image, run it using `docker run -d -p local-port:container-port your-image-name:tag`, adjusting `local-port` and `container-port` as necessary for your application.

3.  Test the Application: With the container running, test your application by accessing it via the local port you specified, using tools like curl, Postman, or your web browser, depending on the nature of your application.

4.  View Logs and Debug: Use `docker logs container-id` to view the logs for troubleshooting if needed.

Deployment
----------

Deployment options include Docker and AWS. AWS deployment utilizes AppSpec and BuildSpec files for automation. Refer to the provided files for specific instructions.

License
-------

This project belongs to [KodeKloud](https://www.kodekloud.com)
