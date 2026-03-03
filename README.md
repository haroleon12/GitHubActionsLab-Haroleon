# GitHubActionsLab-Haroleon

What the workflows do:

Dependent Jobs: Shows how build → test → deploy runs in order using needs. Simulates a real app pipeline.

Multi-Platform: Runs jobs at the same time on Ubuntu, Windows, and macOS. Prints OS info and creates a file. Shows jobs can run in parallel.

Key concepts:

needs: controls job order

runs-on: picks the OS for each job

env: sets variables

Challenges:

Multi-platform didn’t run at first because I hadn’t made a pull request — fixed by creating one to master.

Had to double-check .github/workflows/ folder placement so GitHub would see the workflows.
