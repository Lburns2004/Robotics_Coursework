This coursework implements forward and inverse kinematics, trajectory generation, and collision-aware control of a 4-DOF robotic arm. Using MATLAB and the Robotics Toolbox, the robot autonomously navigates a simulated library to retrieve and shelve books with precision. The project emphasizes analytical IK solutions, optimized grasping strategies, and fluid animation control.

📌 Tasks:
Model the robot arm using Denavit–Hartenberg parameters and verify with a custom URDF.

Solve inverse kinematics analytically to reach book positions and place them on designated shelves.

Integrate collision objects and simulate real-time book grasping using prismatic joints.

Generate realistic trajectories using point-to-point and cosine-interpolation methods.

Build full robot animations for book pickup and placement including intermediate reorientation steps.

🛠 Instructions for Use:
💾 Cloning the Repository
To begin, clone the repository to your local machine:

bash
git clone https://github.com/username/robot-librarian.git
Replace username with the GitHub account holding the repository.

🔧 Making Changes Locally
Navigate into the directory and make changes:

bash
cd robot-librarian
Check the status:

bash
git status
Stage all modifications:

bash
git add .
Commit with a meaningful message:

bash
git commit -m "Update trajectory logic for Book 3"
🚀 Pushing Changes to GitHub
Push updates to the main branch:

bash
git push origin main
If working on another branch, use:

bash
git push origin your-branch-name
🔄 Pulling Updates from GitHub
Keep your repository in sync:

bash
git pull origin main
Or for another branch:

bash
git pull origin your-branch-name
🌿 Creating a New Branch
Create and push a new feature branch:

bash
git checkout -b book-reorientation-fix
git push origin book-reorientation-fix
