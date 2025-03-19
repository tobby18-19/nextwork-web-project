# NextWork Web App Deployment with AWS CI/CD

This project is a Java web application deployed on AWS using a CI/CD pipeline.

## Features
- Hosted on an AWS EC2 instance
- GitHub integration for version control
- Automated deployments using Git and Nginx
- Continuous Integration & Continuous Deployment (CI/CD)

## Prerequisites
Before running this project, ensure you have the following:
- AWS EC2 instance set up
- Git installed (`git --version` to check)
- A GitHub repository connected

## Setup Instructions

1. Clone the repository:
   ```sh
   git clone https://github.com/tobby18-19/nextwork-web-project.git
   cd nextwork-web-project
   ```

2. Initialize Git and connect to GitHub:
   ```sh
   git init
   git remote add origin https://github.com/tobby18-19/nextwork-web-project.git
   ```

3. Stage and commit your changes:
   ```sh
   git add .
   git commit -m "Initial commit"
   ```

4. Push to GitHub:
   ```sh
   git push -u origin master
   ```

## Deployment
To deploy this project on an AWS EC2 instance:

1. SSH into your EC2 instance:
   ```sh
   ssh ec2-user@your-ec2-ip-address
   ```

2. Navigate to the project folder and pull the latest changes:
   ```sh
   cd ~/nextwork-web-project
   git pull origin master
   ```

3. Restart Nginx (if applicable):
   ```sh
   sudo systemctl restart nginx
   ```

## Contributing
Feel free to fork this repository, make your changes, and submit a pull request.

## License
This project is licensed under the MIT License.
```

### Step 3: Save and Push the README.md  
After saving the file, push it to GitHub:

```sh
git add README.md
git commit -m "Added README documentation"
git push origin master
```


