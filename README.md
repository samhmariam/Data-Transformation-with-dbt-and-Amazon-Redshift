# Data-Transformation-with-dbt-and-Amazon-Redshift

This lab walks you through data transformations in Amazon Redshift using dbt core. dbt uses SQL and Jinja to manage data transformations in Amazon Redshift. 

## Steps

### Step 1: Setup the required resources in AWS

1. Setup the required resources in AWS using the CloudFormation template provided in the `IaC` folder.
2. Install dbt and Redshift connector
    - `pip3 install dbt-core`
    - `pip3 install dbt-redshift`
3. Create dbt project using the following command:
    - `dbt init demo-project`
4. Test the connection to Redshift using the following command:
    - `dbt debug`

### Step 2: Create a base model in dbt

1. Create base model in dbt using the following command:
    - `python3 generate_base_tables.py demo_project public`

### Step 3: Create a model in dbt

1. Create a finance model 

### Step 4: Create macros 

### Step 5: Create Hooks

### Step 6: Create Seeds



