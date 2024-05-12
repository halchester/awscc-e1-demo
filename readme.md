### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/halchester/awscc-e1-demo
   ```
2. Have python 3.12.2 installed - [link](https://www.python.org/downloads/release/python-3122/)
3. Have docker installed
4. Build the docker image
   ```sh
   docker build -t awscc-e1-demo .
   ```
5. Run the docker image
   ```sh
    docker run -p 8000:8000 awscc-e1-demo
   ```
6. Open your browser and go to `http://localhost:8000/`
7. You should see the app running
