# Idea for scraping of rozkład-pkp.pl

Django webapp, which scrapes the webpage rozklad-pkp.pl in search of the train connections between cities selected by users, and sends them to their email, listing the time and prices of tickets. The app is going to be deployed to a web server, to make it available for users, who will be given passwords by the administration. Scraping would be done in the batch processes.

# GPT suggestions (check if correct)

## Project Roadmap:

1. Understanding of the requirements and goals of the project.
2. Design and architecture of the Django webapp.
3. Scraping the webpage rozklad-pkp.pl for train connections.
4. Building the user authentication and authorization system.
5. Implementing the batch processes to scrape the train connection data.
6. Integrating the email functionality to send the train connections to users.
7. Testing and debugging of the webapp.
8. Deployment of the webapp to a webserver.

### Three Best Cloud Service Providers for this project:

1. Amazon Web Services (AWS) - AWS offers a wide range of services, including EC2, S3, and Lambda, that are suitable for hosting and deploying Django webapps.
2. Google Cloud Platform (GCP) - GCP provides a scalable, reliable, and secure infrastructure for deploying and running webapps, including Django applications.
3. Microsoft Azure - Azure offers a range of services, including Azure Web Apps and Azure Functions, that make it easy to host and deploy Django webapps. Additionally, Azure provides a secure and reliable infrastructure for storing and processing data.

### Here is a high-level overview of deploying a Django app to one of the cloud service providers listed above:

1. Amazon Web Services (AWS):
  - Choose a suitable EC2 instance to host the Django app.
  - Install and configure the necessary dependencies, such as Django, Python, and Apache.
  - Deploy the Django app to the EC2 instance using Git or other version control tools.
  - Configure the security groups and firewall rules to allow access to the EC2 instance.
  - Create and configure an S3 bucket to store any media or static files required by the app.
  - Integrate the email functionality using AWS Simple Email Service (SES).
  - Launch the Django app and test it to ensure it is accessible to users.
2. Google Cloud Platform (GCP):
  - Choose a suitable App Engine standard environment to host the Django app.
  - Deploy the Django app to the App Engine standard environment using Git or other version control tools.
  - Configure the app to use Google Cloud Storage for storing any media or static files required by the app.
  - Integrate the email functionality using Gmail or Google Workspace.
  - Launch the Django app and test it to ensure it is accessible to users.
3. Microsoft Azure:
  - Choose a suitable Azure Web App to host the Django app.
  - Deploy the Django app to the Azure Web App using Git or other version control tools.
  - Configure the app to use Azure Blob Storage for storing any media or static files required by the app.
  - Integrate the email functionality using Azure SendGrid or Microsoft Office 365.
  - Launch the Django app and test it to ensure it is accessible to users.

Note: This is a high-level overview and there may be additional steps required to deploy the Django app to each platform, such as configuring databases and setting up environment variables.