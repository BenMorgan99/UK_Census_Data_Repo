# UK_Census_Data_Repo

## Project Overview
This project aims to fetch publicly available census data from the ONS public API. An ETL pipeline is then set up using separate Lambda functions to allow the end user to query data from specific timeframes, demographics, geographical location to analyse changes over time.

## Tech Stack

* Python

* PostgreSQL

* Terraform

* AWS

* Github Actions (CI/CD)

## Terraform Pipeline

* Checkout Repository

* Configure AWS Credentials

* Set Up Terraform

* Initialize Terraform (terraform init)

* Validate Configuration (terraform validate)

## Python Pipeline

This pipeline ensures code quality and runs tests:

* Checkout Repository

* Set up Python 3.10

* Install Dependencies (flake8, pytest, moto, etc.)

* Linting with Flake8

* Run Tests with Pytest (including AWS mocking via moto)
