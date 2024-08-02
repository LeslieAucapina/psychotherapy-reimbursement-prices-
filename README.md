# psychotherapy-reimbursement-prices-
Reading and identifying the reimbursement prices of in-network psychotherapy through insurance plans

Effective since 2022, The Transparency in Coverage final ruling requires health plans to publish the prices of their reimbures services publicly in Machine Readable Files

The data is publicly available as a json file. This script runs by having the data stored and reading the files downloaded into the relative directory path in order to be extracted

The data is filtered by CPT code to identify psychotherapy treatments, specifically; 90832, 90834, 90837, 90785, 90833

This script only includes reading the files downloaded into the relative directory path

Columns include: name, billing_code_type, billing_code_type_version, billing_code, provider_group_id, npi, npi_count, provider_reference, negotiated_type, negotiated_rate, expiration_date, and file_name


'Nested_value' is a script first ran to understand a file's structure and the nested dictionaries that will be extracted
'Code' is the final script to extract the data 
