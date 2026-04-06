# n8n_searching_job
# Automated Job Alert System – n8n Project

## Project Overview

This project is an automated job alert system developed using n8n. The purpose of this system is to automatically collect job opportunities from multiple job websites and send them via email to the user. This helps the user stay updated with new job postings without manually checking different websites.

## Objective

The main objective of this project is to automate the process of job searching and notification. The system collects job data from multiple RSS feeds, processes the data, and sends a formatted email containing job opportunities.

## Tools and Technologies Used

* n8n (Workflow Automation Tool)
* Gmail Node (Email Sending)
* RSS Feed Nodes (Data Collection)
* JavaScript (Function Nodes for Data Processing)

## Workflow Description

The workflow consists of several steps:

1. The workflow starts with a manual trigger.
2. The system reads job postings from multiple RSS feed sources such as job websites.
3. The data from different RSS feeds is collected and combined.
4. Function nodes are used to process and store job data temporarily.
5. The system generates an email body that includes job title, job link, and job source.
6. The Gmail node sends an email with the list of job opportunities.
7. After sending the email, the stored job data is cleared to prepare for the next execution.

## System Architecture

User → n8n Workflow → RSS Feeds → Data Processing → Email Notification → User

## Security Considerations

For security reasons, sensitive information such as Gmail OAuth credentials, Client ID, Client Secret, and API keys are stored securely in the n8n credential manager and are not included in the exported workflow JSON file. Personal email addresses were removed from the shared project files for privacy reasons.

## Project Output

The output of this project is an automated email notification containing a list of new job opportunities collected from multiple job websites.

## Screenshot

<img width="1770" height="373" alt="image" src="https://github.com/user-attachments/assets/ee63d680-8d1d-41e2-ab74-f427539549e8" />

<img width="1770" height="373" alt="image" src="https://github.com/user-attachments/assets/cbdf5e75-39a4-43ca-bc66-46f3bb6599e8" />



## Conclusion

This project demonstrates how workflow automation can be used to automate repetitive tasks such as job searching and email notification. The system reduces manual work and ensures that the user receives job updates automatically.

## Author

Student Project – Automation using n8n
