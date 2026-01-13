# Contributing to Tracking-3D-particles

Thank you for your interest in contributing to this project!

## How to Fork This Repository

Forking creates your own copy of this repository under your GitHub account, allowing you to make changes without affecting the original project.

### Step 1: Fork the Repository on GitHub

1. Navigate to [https://github.com/alexlib/Tracking-3D-particles](https://github.com/alexlib/Tracking-3D-particles)
2. Click the **Fork** button in the upper-right corner of the page
3. Select your GitHub account as the destination for the fork
4. Wait for GitHub to create your fork

### Step 2: Clone Your Fork Locally

After forking, clone your copy to your local machine:

```bash
# Replace YOUR-USERNAME with your GitHub username
git clone https://github.com/YOUR-USERNAME/Tracking-3D-particles.git
cd Tracking-3D-particles
```

### Step 3: Configure Upstream Remote

Add the original repository as an upstream remote to keep your fork synchronized:

```bash
git remote add upstream https://github.com/alexlib/Tracking-3D-particles.git
git remote -v
```

You should see:
- `origin` pointing to your fork
- `upstream` pointing to the original repository

### Step 4: Keep Your Fork Up to Date

Regularly sync your fork with the upstream repository:

```bash
# Fetch the latest changes from upstream
git fetch upstream

# Switch to your main branch
git checkout main

# Merge upstream changes into your main branch
git merge upstream/main

# Push the updates to your fork
git push origin main
```

## Making Changes

### Step 1: Create a Feature Branch

Always create a new branch for your changes:

```bash
git checkout -b your-feature-branch-name
```

### Step 2: Make Your Changes

Make your changes to the code, following the project's coding standards.

### Step 3: Commit Your Changes

```bash
git add .
git commit -m "Description of your changes"
```

### Step 4: Push to Your Fork

```bash
git push origin your-feature-branch-name
```

### Step 5: Create a Pull Request

1. Go to your fork on GitHub
2. Click the **Compare & pull request** button
3. Provide a clear description of your changes
4. Submit the pull request

## Getting Help

If you need help or have questions, please:
- Open an issue on the [original repository](https://github.com/alexlib/Tracking-3D-particles/issues)
- Refer to the project's README.md for more information

## Related Paper

This code belongs to the paper: "Deep Learning Based Real-Time 3D Tracking of Multiparticles under Wide Area Illumination"
