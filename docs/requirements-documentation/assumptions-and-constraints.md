---
sidebar_position: 4
---

# Assumptions and constraints

- The application will be developed and tested on a desktop computer running Windows 10, with a modern web browser (such as Google Chrome or Mozilla Firefox) installed.
- The application will be deployed to a cloud-based virtual machine running Ubuntu Linux.
- The virtual machine will have a public IP address and will be accessible via the internet.
- The virtual machine will have Docker installed and will be used to containerize the application.
- The application will be deployed to the virtual machine using a continuous integration and delivery (CI/CD) pipeline.
- The pipeline will consist of a version control system (such as Git), a build server (such as Jenkins), and a deployment tool (such as Ansible).
- The pipeline will automatically build and deploy the application whenever new code is pushed to the version control repository.
- The pipeline will automatically run unit tests to ensure that the application is functioning properly.
- The application will be accessible via a domain name (such as todolist.example.com) that will be registered and pointed to the public IP address of the virtual machine.
- The application will use a MySQL database to store the tasks and other application data.
- The database will be hosted on a separate virtual machine or cloud-based service (such as Amazon RDS or Google Cloud SQL).
- The database will be accessed via a secure connection (such as SSL or TLS).
