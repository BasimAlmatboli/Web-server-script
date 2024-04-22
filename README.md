# AWS EC2 Web Server Setup Script

This Bash script automates the setup of a web server on an Amazon EC2 instance running Amazon Linux 2023. It installs Apache HTTP Server or Nginx Server, fetches the instance ID from the EC2 metadata service, and displays it along with a random cat picture from the Cat API on a custom web page.

## Prerequisites

- An Amazon EC2 instance running Amazon Linux 2023.
- Internet access from the EC2 instance to fetch resources from external sources such as the Cat API.

## Installation

1. SSH into your Amazon EC2 instance.
2. Clone this repository or download the Bash script directly.

   ```bash
   git clone https://github.com/your-username/your-repo.git


## Usage
Once the script execution is complete, you can access the custom web page by navigating to your EC2 instance's public IP address or DNS name in a web browser.

## Customization
- Cat Picture: You can customize the cat picture by modifying the URL in the script (http://thecatapi.com/api/images/get?format=src&type=gif&api_key=8f7dc437-0b9b-47b8-a2c0-65925d593acf).
- Web Page Content: Modify the HTML content in the script to customize the appearance and layout of the web page.

## Troubleshooting
- If you encounter any errors during script execution, refer to the script's comments for guidance on troubleshooting each step.
- Ensure that your EC2 instance has internet access to fetch resources from external sources.

  
## Contributors
Basim Mohamed
