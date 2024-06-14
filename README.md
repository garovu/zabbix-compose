# Zabbix set-up with docker-compose

This repository provides a docker-compose configuration for setting up Zabbix monitoring system.

## Prerequisites

Before getting started, make sure you have the following installed on your system:

- Docker
- Docker Compose

## Usage

1. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/your-username/zabbix-compose.git
    ```

2. Navigate to the cloned repository:

    ```bash
    cd zabbix-compose
    ```

3. Customize the `docker-compose.yml` file according to your needs. You can modify the Zabbix version, database credentials, and other settings.

4. Start the Zabbix containers:

    ```bash
    docker-compose up -d
    ```

5. Access the Zabbix web interface:

    Open your web browser and navigate to `http://localhost:8080`. You will be prompted to set up the Zabbix database.

6. Follow the on-screen instructions to complete the Zabbix installation.

7. Once the installation is complete, you can log in to the Zabbix web interface using the default credentials:

    - Username: Admin
    - Password: zabbix

## Configuration

The `docker-compose.yml` file allows you to configure various aspects of the Zabbix setup, including:

- Zabbix version
- Database credentials
- Web server settings
- Zabbix agent settings

Please refer to the [Zabbix documentation](https://www.zabbix.com/documentation) for more information on configuring Zabbix.
