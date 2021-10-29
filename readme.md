# ZC Messaging

This plugin handles messaging for both DM and Channels

## Project Structure

This project is a monolith application. You will find two folders namely:

1. backend
2. frontend

Depending on your track, you are to work in the folder that concerns you.

## Setup

### Backend

- Fork this repository to have a copy of it in your own github account
- Clone the forked repo to your PC, this gives you access to the repo locally
- Install Python from <https://www.python.org/downloads/> if you haven't
- cd into the project folder
- cd into the backend folder
- Ensure a virtual environment has been created and activated by either using
  - For pipenv

    ```bash
    pipenv shell #creates and activates a virtual environment
    ```

  - For venv

    ```bash
    python -m venv venv # to create a virtualenv
    source venv/bin/activate # activate for linux
    venv\Scripts\activate # activate for windows
    ```

- Run the startup.sh script to install dependencies and start up server by typing out this command on your terminal(Linux, Mac) or Git bash (Windows)

    ```bash
    sh startup.sh venv # starts script to use virtualenv
    sh startup.sh pipenv # starts script to use pipenv
    ```

- Server can also be manually started by using the following command

    ```bash
    uvicorn main:app --reload
    ```

### Frontend

Guides for Frontend will be updated soon

## Technologies Used

1. Backend: FastApi
2. Frontend: React
