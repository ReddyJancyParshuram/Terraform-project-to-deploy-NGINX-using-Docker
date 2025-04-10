🐳 Terraform Project to Deploy NGINX using Docker
This is a mini project that uses Terraform to automate the deployment of an NGINX container using Docker.

📁 Project Structure
terraform-docker-container/
├── main.tf               # Terraform configuration for Docker and NGINX
├── .gitignore            # Git ignore file to skip unnecessary files
├── terraform.tfstate     # Terraform state file (auto-generated, ignored in Git)
├── terraform.tfstate.backup
└── README.md             # Project description

⚙️ Technologies Used
🧱 Terraform (Infrastructure as Code)
🐳 Docker (Containerization)
🌐 NGINX (Web Server)

🚀 Steps to Run the Project
Initialize Terraform -- terraform init
Preview the deployment -- terraform plan
Apply and launch the NGINX container -- terraform apply --auto-approve

✅ What This Does
Pulls the latest NGINX image from Docker Hub.
Spins up a Docker container running NGINX.
All done with a few lines of Terraform code!
🔗 Once deployed, you can access the NGINX server at: http://localhost:8081

📌 Notes
Make sure Docker is running before you apply the Terraform configuration.
You can access the running NGINX container on your local machine once it’s up.

### 📤 Next Steps: Save, Commit, and Push

1. Open `README.md` in your project folder
2. Replace the existing content with the above updated version
3. Save the file
4. Run these commands in your terminal:
git add README.md
git commit -m "Updated README with localhost access link"
git push origin main





