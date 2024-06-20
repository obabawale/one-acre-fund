# one-acre-fund
Take-home test for One-acre fund

## How to Run This Project
The project is set up to be run with docker compose. Please note that you need to have docker engine and docker compose installed on your machine before using this approach. Below are the instructions on how to run this project:

- 1. Clone the repository.
```bash
    git clone --recurse-submodules https://github.com/obabawale/one-acre-fund
```

- 2. Once the repository has been clone. Go into the folder
`
    cd one-acre-fund
`

- 3. From inside the folder, configure the odoo server configuration properties by setting the right parameters in config/odoo.conf file and set the database user password in odoo_pg_pass file.
  
- 4. Once all the steps above have been completed successfully, the containers can be started up with the following command:
`bash
    docker compose up -d
`