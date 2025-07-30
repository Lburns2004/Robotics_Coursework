This coursework implements forward and inverse kinematics, trajectory generation, and collision-aware control of a 4-DOF robotic arm. Using MATLAB and the Robotics Toolbox, the robot autonomously navigates a simulated library to retrieve and shelve books with precision. The project emphasizes analytical IK solutions, optimized grasping strategies, and fluid animation control.

---

## 📌 Tasks:
Model the robot arm using Denavit–Hartenberg parameters and verify with a custom URDF.

- Solve inverse kinematics analytically to reach book positions and place them on designated shelves.
- Integrate collision objects and simulate real-time book grasping using prismatic joints.
- Generate realistic trajectories using point-to-point and cosine-interpolation methods.
- Build full robot animations for book pickup and placement including intermediate reorientation steps.

---

<img width="1988" height="1536" alt="Isometric View Render" src="https://github.com/user-attachments/assets/7e933257-0f6c-4243-b584-b69d7d28d6e0" />

---

Cloning the Repository

To start working on the project, first, clone the repository to your local machine.
Go to the GitHub repository link (e.g., https://github.com/username/repository-name).
Click the green Code button, then copy the URL of the repository.
Open Git Bash (or any terminal you prefer) and navigate to the folder where you want to clone the project.
Use the following command to clone the repository: git clone https://github.com/username/repository-name.git
Making Changes Locally Once the repository is cloned to your machine, navigate into the project directory where you want to make changes.

To check the status of your repository and see what has changed, use: git status
To add the modified files to the staging area, use: git add .
After adding the changes, commit them with a message describing what you've done: git commit -m "Your commit message"
Pushing Changes to GitHub Once you’ve committed your changes locally, the next step is to push those changes to GitHub to update the remote repository.

Use the following command to push your changes: git push origin main
If you're working on a branch other than main, replace main with the name of the branch you’re using.

Pulling Changes from GitHub To make sure your local repository is up-to-date with the latest changes made by others, you should pull the latest updates from GitHub.

Use the following command to pull the changes: git pull origin main
If you're working with a different branch, replace main with the name of that branch.
Creating a New Branch Creating a new branch allows you to work on a specific feature or fix without affecting the main codebase. Here’s how you can create and work on a new branch:

To create a new branch, use: git checkout -b new-branch-name
After making changes and committing them, push the new branch to GitHub using: git push origin new-branch-name
