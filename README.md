# Soda Core project dbt results ingestion example
- Make sure you have a Soda Cloud account
- Update config.yml with your Soda Cloud API KEY and SECRET
- Install soda-core-dbt package using `pip install soda-core-dbt`
- Run command:  `soda ingest dbt -d jaffle_dbt -c config.yml --dbt-artifacts dbt`

PS: The dbt artifacts are generated using `dbt test` on https://github.com/dbt-labs/jaffle_shop project. 
