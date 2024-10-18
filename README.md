# Airbyte Installation Guide

This guide will walk you through the process of setting up Airbyte using Docker Compose.

## Prerequisites

Make sure you have the following installed:
- [Git](https://git-scm.com/)
- [Docker](https://www.docker.com/)
- [Docker Compose](https://docs.docker.com/compose/)

## 1. Clone the Airbyte Repository

Clone the Airbyte repository using the following command:

```bash
git clone --depth=1 https://github.com/airbytehq/airbyte.git
```

## 2. Start Airbyte

Once the repository has been cloned, navigate to the Airbyte directory and start the platform using the following script:

```bash
cd airbyte
./run-ab-platform.sh
```


## 3. Access the Airbyte Platform

   Access the user interface at the following link: [http://localhost:8000](http://localhost:8000). The initial login credentials for Airbyte are:

   - **Username**: `airbyte`
   - **Password**: `password`

   You can change these credentials as needed.