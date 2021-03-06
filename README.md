# flask_web_app_on_docker

Run these commands from a terminal:

1. Clone this repo: `git clone https://github.com/waleadekoya/flask_web_app_on_docker.git`
2. Change directory: `cd flask_web_app_on_docker`

## Requirements:

**Docker** must be installed.
You can download and install docker instance specific to your platform and Operating System from this link:
[Docker Download](https://hub.docker.com/search?offering=community&q=&type=edition)

You also need to configure a relational database and upload data in `"ProductDataForDB.xlsx"` file for the models to work.

Configure the database uri as class variable in this file: `"controls/config.py"` (not shared - use similar structure in `"config.py"`)

Configure system environment variables in this file: `"controls/.env"` (not shared)

**To build and run the flask server**:

3. On Windows: double-click this file: `run_app.bat` OR on ALL platforms use: `docker-compose up`


Navigate to https://localhost:8041 on your browser.
