# SQL+Python+Rstudio Docker Environment
**Description**: Dockerfiles and docker compose for SQL and Python environment for   STAT 624

## Quick start guide
1. Download zipped folder containing all files in this repository.
2. Unzip folder and store in local directory of your choosing. (if you are building postgresql image, first extract 'datadump.sql' and save it at the same directory)
3. In a terminal window, navigate to the local directory containing `docker-compose.yml`.
4. Open Docker Desktop. In terminal, run the command `docker compose up`.  The Docker images will be downloaded to your system and containers will be created accordingly.
5. Open a web browser window and type `localhost:5050` to open pgAdmin4 GUI to interact with the database.
6. In a different web browser tab, copy and paste the custom URL provided in the terminal window to access the Jupyter notebook environment to interact with the database.  

