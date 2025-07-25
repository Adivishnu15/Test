## 🔁 Experiment 1: Source Code Management on GitHub

This experiment demonstrates how to manage source code using Git and GitHub. We use a simple **Student Event Registration Form** built with HTML and CSS and push it to a GitHub repository.

---

### 📝 Files to Create

1. `registration.html` – The student registration form
2. `register.css` – The associated CSS styling

📁 You can clone the reference code using:
```bash
git clone https://github.com/Adivishnu15/Test.git
📤 Push Code to Your Own GitHub Repository
✅ Step-by-step Instructions
Create a new repository on GitHub
👉 Example: https://github.com/<yourusername>/Student-Registration.git

Open Terminal in Your Project Folder
Navigate to the folder containing registration.html and register.css

Run the following commands:

bash
Copy
Edit
# Optional: Update system & install Git
$ sudo apt-get update
$ sudo apt-get install git        # (only if git is not installed)

# Check Git version
$ git --version

# Initialize a local Git repository
$ git init

# Configure Git (first time only)
$ git config --global user.name "Your Name"
$ git config --global user.email "youremail@example.com"

# Add files to staging area
$ git add registration.html register.css
# OR to add all files:
# $ git add .

# Commit the changes
$ git commit -m "Initial commit - student registration"

# Add the remote repository URL
$ git remote add origin https://github.com/<yourusername>/Student-Registration.git

# Set branch name to main
$ git branch -M main

# Push code to GitHub (you may need a personal access token)
$ git push -u origin main
🔐 GitHub Authentication
If prompted for a username and password:

GitHub no longer accepts passwords for command-line Git.

Instead, use a Personal Access Token (PAT):

Go to: GitHub → Settings → Developer settings → Personal access tokens

Generate a token with repo access

Use it as your password in the terminal

✅ Outcome
Your HTML and CSS files will now be visible in your GitHub repository. You have successfully managed and version-controlled your student registration form using Git!
