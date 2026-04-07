Task 1:

Field = full_name	
Type = Direct PII	
Action = Drop

Field = email	
Type = Direct PII	
Action = Drop

Field = date_of_birth	
Type = Indirect PII	
Action = Mask

Field = zip_code	
Type = Indirect PII	
Action = Mask

Field = job_title	
Type = Indirect PII	
Action = Mask

Field = diagnosis_notes	
Type = Indirect PII
Action = Pseudonymize


Task 2:

1. the script violates API terms of service by using a free-tier API key to perform bulk data extraction and then storing all records permanently.
2. time.sleep(1) is missing. the script should limit the number of requests.
3. misuse of Free-Tier API for permanent storage.
4. collecting sensitive data without control
