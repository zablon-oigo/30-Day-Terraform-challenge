# Day 7: Understanding Terraform State Part 2

## Overview

Welcome to Day 7 of the Terraform 30-Day Challenge! Today, we will continue exploring Terraform state management, focusing specifically on state isolation. You'll learn how to isolate Terraform state through Workspaces and through file layouts, and the advantages of each method. By the end of today, you will have separate environments configured and a deep understanding of how to manage state isolation for different use cases.

## Tasks for Today

### 1. **Reading**
   - **Chapter**: Complete Chapter 3 (Pages 81-113)
     - Sections: "State File Isolation", "Isolation via Workspaces", "Isolation via Files Layout", and "The Remote State Source".
   - **Goal**: Understand the two primary methods of state isolation and how to manage state across different environments.

### 2. **Hands-on Labs**
   - **Lab**: Complete the following hands-on labs:
     - "Lab 08: State Management"
     - "Lab 09: State Locking"
   - **Goal**: Gain hands-on experience with Terraform through practical exercises.
### 3. **Activity**
   - **State Isolation Practice**: Practice both methods of state isolation:
     - **Workspaces**: Set up isolated environments using Workspaces for different environments (e.g., dev, staging, production).
     - **File Layouts**: Organize separate environments using isolated file layouts for each environment.
   - **Goal**: Successfully configure isolated environments using both Workspaces and file layout methods. Understand the differences and when to use each approach.

### 4. **Bonus Hands-On Project**
   - **Goal**: Configure remote state storage using AWS S3 or an equivalent service in another cloud provider. Lock the state file to prevent conflicts and observe the behaviour in a team environment. 
   - **Steps**: Set up remote state storage and state locking across your isolated environments. Test how state locking works when multiple users try to update the infrastructure simultaneously.

### 5. **Blog Post**
   - **Title**: "State Isolation: Layout vs Workspace"

### 6. **Social Media Post**
   - **Text**: "🗂 Learned how to manage Terraform state effectively today. Crucial for consistent deployments. #30daytfchallenge #HUG #hashicorp #HUGMERU @awsaimlkenyaug #IaC"

## How to Submit Your Work

### 1. **Create the `day7-update-your-github-username.md` File**
   - Include your Terraform code and any architecture diagrams in the markdown file.
   - Document your setup for both Workspace isolation and File Layout isolation, including any challenges faced and how you resolved them.
   - Save the file in your `day7-state-isolation` branch.

### 2. **Commit Your Changes**
   - Stage and commit your changes with a message like:
     ```bash
     git add day7-update-your-github-username.md
     git commit -m "Completed Day 7 task on state isolation via workspace and layout"
     ```

### 3. **Create a Pull Request**
   - Push your changes to your GitHub repository:
     ```bash
     git push origin day7-state-isolation
     ```
   - Create a pull request using the provided template and include any additional comments if necessary.

## Checklist

- [x] I have completed Chapter 3 of "Terraform: Up & Running".
- [ ] I have completed the required hands-on labs
- [x] I have successfully configured state isolation using both Workspaces and File Layout methods.
- [x] I have configured remote state storage and state locking as part of the Bonus Hands-On Project.
- [ ] I have written and published a blog post about today's task.
- [x] I have made a social media post about today's task.
- [x] I have created a `day7-update-your-github-username.md` file with my Terraform code and architecture diagrams.
- [x] I have created a pull request with all the required details.

## Additional Resources

- [Terraform: Up & Running on Amazon](https://www.amazon.com/Terraform-Running-Infrastructure-Configuration-Management/dp/1492046906)

- [Documentation on Terraform Workspaces](https://www.terraform.io/docs/language/state/workspaces.html)





