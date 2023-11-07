# CSCI 5253: Datacenter-scale computing

In this repository, you'll find the files for the labs for the CSCI 5253 course for Fall '23.

Our goal is to build up a scalable data pipeline processing data from Austin Animal Shelter Outcomes over the course of the semester.

Lab 1:
- Create a dockerized script reading data from a csv, processing it, and outputting into another csv

Lab 2:
- Create a dockerized postgres data warehouse to store the data
- Use dimensional modeling for the data
- Load the data into the DW through docker-compose

Lab 3:
- Change the pipeline to put the intermediate data into cloud storage at every step
- Switch postgres DW to cloud DW
- Orchestrate the pipeline with Airflow
