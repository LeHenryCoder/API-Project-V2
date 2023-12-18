# API-Project-V2
This is a second version of my prior repo. The reason in in the README file

# Simple Python Banking API

## Description
This project focuses on building a **Simple Python Banking API** using AWS Cloud9. Designed to simulate basic banking operations, it offers a platform for learning API development and cloud integration. Implemented in Python, it showcases the structure and development of a RESTful API for banking functions.

## Key Features
- **Account Information Retrieval**: Fetch basic account details like account number, balance, and account type.
- **Transaction History**: View a list of recent banking transactions.
- **Simple and Scalable Design**: Maintains simplicity while being scalable for future enhancements.

## Technologies Used
- **Python**: For API endpoints and business logic.
- **AWS Cloud9**: As the cloud-based IDE for development.
- **Git and GitHub**: For version control and source code management.

## Learning Objectives
- Master RESTful API development in Python.
- Gain practical experience with AWS Cloud9.
- Explore version control with Git and GitHub.

## Project Status
- **Current Phase**: Development
- **Contribution**: Open to contributions, suggestions, and feedback.

## Lessons Learned in Version 1.0
In the initial version of this project, I encountered a couple of key issues that significantly impacted the project structure and my development experience:

- **Incorrect Order of Resource Creation**: I created an EC2 instance before setting up a VPC (Virtual Private Cloud). This led to a situation where the EC2 instance wasn't in the VPC, and that is a no no. I mean I could've tried to intertwine different VPC's together, but my brain would have actually exploded.

- **Integration Challenges with GitHub**: I almost lost my mind trying to connect GitHub to AWS Cloud9. The process was pretty straight forward but I was eating food and watching a movie while I was connected my aws c9 environment to GitHub, so...... It ended up taking 3 hours...

### Key Takeaways
- **Importance of VPC First Approach**: Starting with a VPC setup in AWS before provisioning other resources like EC2 instances ensures that all components of the project are correctly networked and secure from the outset.
- **Persistence in Problem-Solving**: The challenges with GitHub integration taught me the value of persistence and patience in troubleshooting and problem-solving in software development.

