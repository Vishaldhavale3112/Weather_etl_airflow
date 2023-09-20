# Weather_etl_airflow

#create a EC2 instance on AWS.

# Install python 3 on ec2 and create virtual env 
1) sudo apt update
2) sudo apt install python3-pip
3) sudo apt install python3.10 venv
4) python3 -m venv airflow_venv

# activate virtual env
1) source airflow_venv/bin/activate
2) sudo pip install pandas
3) sudo pip install s3fs
4) sudo pip install apache-airflow
5) airflow standalone

