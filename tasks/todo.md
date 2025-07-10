# SampleProj Todo List

## Project Setup
- [x] Create project directory structure
- [x] Create tasks/todo.md file
- [x] Add basic Python files as needed
- [ ] Set up virtual environment (if required)
- [ ] Add requirements.txt (if dependencies needed)

## Development Tasks
- [ ] Define project requirements
- [ ] Implement core functionality
- [ ] Add error handling
- [ ] Write tests

## Git Commands Reference

### Creating a New Python Project from Scratch and Pushing to GitHub

#### 1. Initial Project Setup
```bash
# Create project directory
mkdir your-project-name
cd your-project-name

# Initialize git repository
git init

# Create basic Python file
touch main.py
# Add your Python code to main.py

# Create project structure
mkdir tasks
touch tasks/todo.md
# Add your project documentation
```

#### 2. Initial Git Commit
```bash
# Add all files to staging
git add .

# Create initial commit
git commit -m "initial upload"
```

#### 3. GitHub Repository Setup
1. Go to GitHub.com and sign in
2. Click "New" to create a repository
3. Name your repository (e.g., "your-project-name")
4. **Important:** Do NOT initialize with README/gitignore (since you have local commits)
5. Create repository and copy the URL

#### 4. Connect Local Repository to GitHub
```bash
# Add remote repository (replace with your GitHub URL)
git remote add origin https://github.com/yourusername/your-project-name.git

# Verify remote was added
git remote -v
```

#### 5. Push to GitHub
```bash
# If repository is empty, push directly
git push -u origin main

# If repository has content (README, etc.), merge first
git pull origin main --allow-unrelated-histories --no-rebase
git push -u origin main
```

#### 6. Verify Success
```bash
# Check status
git status

# Should show: "Your branch is up to date with 'origin/main'"
```

#### Future Updates
```bash
# For subsequent changes
git add .
git commit -m "your commit message"
git push
```

## Review Section

### Initial Project Setup Complete
**Date:** 7/10/2025

**Changes Made:**
1. Created `sampleProj` directory structure
2. Added `tasks/todo.md` for project task tracking
3. Created `main.py` with basic Python application entry point
4. Established simple project foundation ready for development
5. Successfully pushed project to GitHub at https://github.com/ahearnz12/SampleProj

**Project Structure:**
```
sampleProj/
├── main.py           # Main application entry point
├── README.md         # GitHub repository documentation
└── tasks/
    └── todo.md       # Task tracking and project notes
```

**Git Setup Complete:**
- Local repository initialized and connected to GitHub
- Remote tracking configured (origin/main)
- All project files successfully pushed to GitHub
- Ready for collaborative development

**Next Steps:**
- Define specific application requirements
- Set up virtual environment if needed
- Add functionality to main.py based on project goals

**Notes:**
- Project follows simplicity principle with minimal initial structure
- Ready for Python development with basic foundation in place
- Git workflow documented for future reference
