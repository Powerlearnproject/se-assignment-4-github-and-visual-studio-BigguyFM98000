[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/GvXCZgfk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15339401&assignment_repo_type=AssignmentRepo)
# SE-Assignment-4
Assignment: GitHub and Visual Studio
Instructions:
Answer the following questions based on your understanding of GitHub and Visual Studio. Provide detailed explanations and examples where appropriate.

Questions:
Introduction to GitHub:
What is GitHub, and what are its primary functions and features? Explain how it supports collaborative software development.
GitHub is a web-based platform that leverages Git, a distributed version control system, to facilitate software development and collaboration.

Primary Functions and Features:
1. Version Control: GitHub allows developers to manage and track changes to their codebase using Git. This helps in maintaining a history of changes, reverting to previous versions, and branching out for new features or bug fixes.
2. Repositories: A repository (repo) on GitHub is a storage space where project files are kept. Repositories can be public or private and can contain multiple branches for different versions of a project.
3. Branches: Developers can create branches to work on features, bugs, or experiments independently of the main (or master) branch. Once changes are ready, they can be merged back into the main branch.
4. Pull Requests: When changes in a branch are ready to be reviewed and potentially merged into another branch, developers create pull requests. This feature allows team members to discuss and review the changes before they are integrated.
5. Issues: GitHub issues serve as a way to track bugs, enhancements, tasks, and other project-related items. They can be assigned to team members, labeled, and linked to pull requests.
6. Projects: GitHub offers project boards similar to Kanban boards, where developers can organize and prioritize work. This helps in visualizing the progress and workflow of a project.
7. Actions: GitHub Actions enable continuous integration and continuous deployment (CI/CD). Developers can automate workflows to build, test, and deploy their code.
8. Wiki: Each repository can have its own wiki, where documentation and other resources can be stored and collaboratively edited.
9. Code Review: GitHub provides tools for code review, including inline comments, change requests, and approval mechanisms, which help maintain code quality and facilitate knowledge sharing.
10. Community and Collaboration: GitHub fosters community engagement through features like stars (to mark projects as favorites), forks (to create a copy of a repository for personal use), and discussions.

Supporting Collaborative Software Development:
1. Distributed Collaboration: GitHub supports distributed teams by allowing multiple developers to work on the same project from different locations. Each developer can clone the repository, work locally, and push their changes back to the shared repository.
2. Change Tracking and History: GitHub keeps a comprehensive history of all changes made to the codebase. This makes it easy to track who made which changes and when, and to understand the evolution of the project.
3. Branching and Merging: Branching allows developers to work on isolated features or fixes without affecting the main codebase. Merging combines these changes back into the main branch, enabling parallel development and smooth integration of new features.
4. Pull Requests and Code Review: Pull requests are a core feature for collaboration, allowing developers to review each other's code, discuss improvements, and ensure quality before merging changes. This process promotes knowledge sharing and collective code ownership.
5. Issue Tracking: GitHub issues help teams manage and prioritize their work, track bugs, and discuss feature requests. This centralized issue tracking system ensures that everyone is aware of the current state of the project.
6. Project Management: GitHub's project boards and integrated issue tracking support agile methodologies, making it easier for teams to plan sprints, track progress, and adapt to changes.
7. Automation with Actions: GitHub Actions automate repetitive tasks like testing, building, and deploying code. This ensures consistent processes and frees up developers to focus on more complex tasks.
8. Documentation and Wikis: GitHub wikis and README files provide a centralized place for project documentation, making it easier for new contributors to get up to speed and for teams to maintain comprehensive project information.
9. Community Contributions: Public repositories encourage community contributions. Open source projects on GitHub benefit from a global pool of contributors who can fork repositories, suggest improvements, and submit pull requests.

Repositories on GitHub:
What is a GitHub repository? Describe how to create a new repository and the essential elements that should be included in it.
A GitHub repository (often referred to as a "repo") is a storage space where a project’s files and the history of changes made to those files are kept. Repositories can contain folders and any type of files (code, text, images, data sets, etc.). They also track the history of changes, enabling collaboration and version control.

Creating a New Repository:
Sign In to GitHub:
Navigate to GitHub and sign in to your account.

Create a New Repository:
Click on the "+" icon in the upper right corner of the page.
Select "New repository" from the dropdown menu.

Configure the Repository:
Repository Name: Enter a unique name for your repository.
Description (optional): Add a short description of your project.
Visibility: Choose between:
Public: Anyone on the internet can see this repository. You choose who can commit.
Private: You choose who can see and commit to this repository.
Initialize with a README: Check this box to automatically include a README file.
Add .gitignore: Choose a .gitignore template suitable for your project type (optional). This file specifies which files should be ignored by Git.
Choose a license: Select a license for your project (optional). This defines how others can use your project.

Create Repository:
Click the "Create repository" button to finalize the creation of your repository.

Essential Elements to Include in a Repository:
1. README.md - The README file is the first thing someone sees when they visit your repository.
2. .gitignore - This file tells Git which files (or patterns) it should ignore. 
3. LICENSE - Including a license file is important if you want to explicitly state the terms under which others can use, modify, and distribute your project.
4. CONTRIBUTING.md - This file provides guidelines for contributing to your project.
5. CODE_OF_CONDUCT.md - This file outlines the standards for behavior in your community and provides guidelines for reporting unacceptable behavior.
6. Documentation - Depending on the complexity of your project, you may include additional documentation.
7. Changelog - A changelog documents all notable changes made to a project.
8. Source Code - The actual code files for your project.
9. Tests - Including tests (unit tests, integration tests, etc.) helps ensure the integrity of your project.
10. CI/CD Configuration - If you’re using continuous integration/continuous deployment (CI/CD) tools like GitHub Actions, you’ll include configuration files (e.g., .github/workflows/).

Version Control with Git:
Explain the concept of version control in the context of Git. How does GitHub enhance version control for developers?
Version control is a system that records changes to a file or set of files over time so that you can recall specific versions later. In software development, it allows multiple developers to work on a project simultaneously, without overwriting each other’s changes. Git is a distributed version control system that is widely used for managing source code changes.

How GitHub Enhances Version Control for Developers
Centralized Collaboration:
GitHub acts as a central hub for repositories, making it easy for developers to collaborate. Team members can clone the repository, make changes, and push updates to the same central location.

Pull Requests:
Pull requests are a core feature of GitHub that facilitate code review and discussion. Developers can propose changes, request reviews from teammates, discuss modifications, and iterate on the code before merging it into the main branch.

Issues and Bug Tracking:
GitHub provides a robust issue tracking system where developers can report bugs, request features, and manage tasks. Issues can be linked to commits and pull requests, providing context and traceability.

Continuous Integration/Continuous Deployment (CI/CD):
GitHub Actions enables automation of workflows, including building, testing, and deploying code. This ensures that code changes are continuously integrated and deployed, maintaining code quality and accelerating the development process.

Code Review and Comments:
GitHub offers tools for in-line code comments, reviews, and approvals. This facilitates peer reviews, improves code quality, and fosters collaborative development.

Branch Protection Rules:
Repository administrators can set branch protection rules to enforce certain workflows, such as requiring pull request reviews before merging, preventing force-pushes, and ensuring that all tests pass before changes are merged.

Project Management:
GitHub includes project management tools like project boards (similar to Kanban boards) to organize and prioritize work, track progress, and manage the workflow of a project.

Wikis and Documentation:
Each repository can have its own wiki and README files for documentation. This helps in maintaining comprehensive project documentation and making it accessible to all contributors.

Community and Open Source:
GitHub fosters a community of developers and open-source projects. Public repositories allow developers from around the world to contribute, share knowledge, and collaborate on projects.

Visibility and Integration:
GitHub integrates with many third-party tools and services, enhancing the overall development workflow. It provides visibility into the project’s status, history, and contributions.

Branching and Merging in GitHub:
What are branches in GitHub, and why are they important? Describe the process of creating a branch, making changes, and merging it back into the main branch.
Branches in GitHub represent different lines of development within a repository. Each branch is a unique copy of the repository's files and their history. The default branch, often named main or master, is typically the main line of development.

Importance of Branches
1. Isolated Development: Branches allow developers to work on new features, bug fixes, or experiments in isolation from the main codebase. This means that changes in one branch do not affect the main branch until they are explicitly merged.
2. Parallel Workflows: Multiple branches enable different team members to work on different features or fixes simultaneously without interfering with each other’s work.
3. Safe Experimentation: Developers can experiment with new ideas in separate branches without the risk of breaking the main codebase. If the experiment fails, the branch can be deleted without affecting the main branch.
4. Code Review and Collaboration: Branches facilitate code reviews and collaboration. Developers can create pull requests to discuss, review, and approve changes before merging them into the main branch.
5. Continuous Integration: Branches can be integrated with CI/CD pipelines to automate testing and deployment processes for different versions of the codebase.

Pull Requests and Code Reviews:
What is a pull request in GitHub, and how does it facilitate code reviews and collaboration? Outline the steps to create and review a pull request.
A pull request (PR) in GitHub is a feature that allows developers to notify team members about changes they've pushed to a branch in a repository. It provides a way to review, discuss, and merge changes into another branch (typically the main branch). Pull requests are central to GitHub’s workflow for collaborative development.

How Pull Requests Facilitate Code Reviews and Collaboration
1. Code Review: Pull requests allow team members to review changes before they are merged into the main branch. This process helps in maintaining code quality, catching bugs, and ensuring that coding standards are met.
2. Discussion and Feedback: Developers can comment on specific lines of code, ask questions, and suggest improvements. This facilitates a collaborative discussion around the code changes.
3. Continuous Integration: Pull requests can be integrated with CI/CD pipelines to automatically run tests and build the project, ensuring that new changes do not break the existing codebase.
4. Documentation of Changes: Pull requests provide a history of changes and the discussions around them, which can be useful for future reference.
5. Conflict Resolution: Pull requests highlight conflicts with the base branch, allowing developers to resolve them before merging.

Steps to Create and Review a Pull Request
Creating a Pull Request
Push Changes to a Branch:
Ensure you have a separate branch for your changes.
Commit your changes and push the branch to GitHub.
git add .
git commit -m "Add new feature"
git push origin feature-branch

Navigate to the Repository on GitHub:
Go to the GitHub website and navigate to your repository.

Create a New Pull Request:
Click on the "Pull requests" tab.
Click the "New pull request" button.

Select Branches:
In the "Compare" dropdown, select the branch with your changes (e.g., feature-branch).
In the "Base" dropdown, select the branch you want to merge into (e.g., main).

Review Changes:
Review the changes in the pull request to ensure everything is correct.

Add Title and Description:
Add a title that summarizes the changes.
Write a detailed description of what the pull request does, why the changes were made, and any additional context.

Create the Pull Request:
Click the "Create pull request" button.

Reviewing a Pull Request
1. Open the Pull Request:
Navigate to the repository on GitHub.
Click on the "Pull requests" tab.
Select the pull request you want to review.

2. Review the Code Changes:
Browse through the "Files changed" tab to see the diffs.
Add comments on specific lines if needed by clicking the "+" icon next to the line numbers.

3. Provide Feedback:
Use the comment box to provide overall feedback.
You can also request changes if necessary by clicking "Request changes" and describing what needs to be modified.

4. Approve the Pull Request:
If the changes are satisfactory, click "Review changes".
Select "Approve" and optionally leave a comment.
Click "Submit review".

5. Merge the Pull Request (if you have the necessary permissions):
Click the "Merge pull request" button.
Confirm the merge by clicking "Confirm merge".

6. Delete the Branch (optional but recommended):
After merging, you can delete the branch to keep the repository clean by clicking the "Delete branch" button.

GitHub Actions:
Explain what GitHub Actions are and how they can be used to automate workflows. Provide an example of a simple CI/CD pipeline using GitHub Actions.
GitHub Actions is a feature of GitHub that allows you to automate workflows directly in your repository. You can build, test, and deploy your code right from GitHub, making it a powerful tool for continuous integration and continuous deployment (CI/CD). GitHub Actions uses YAML syntax to define workflows, which consist of one or more jobs that run on virtual machines.

How GitHub Actions Automate Workflows
GitHub Actions can automate various tasks, such as:
1. Continuous Integration (CI): Automatically build and test your code whenever changes are pushed to your repository.
2. Continuous Deployment (CD): Automatically deploy your application to various environments after successful builds.
3. Automation: Automate repetitive tasks like code linting, dependency management, and version bumping.
4. Custom Workflows: Create custom workflows for tasks like code reviews, issue triaging, and notification management.

Introduction to Visual Studio:
What is Visual Studio, and what are its key features? How does it differ from Visual Studio Code?
Visual Studio is an integrated development environment (IDE) from Microsoft. It is a comprehensive suite of tools for software development that supports various programming languages and platforms.

Key Features of Visual Studio
1. Code Editor: Advanced code editing features, including IntelliSense for code completion, syntax highlighting, and code refactoring.
2. Debugging: Powerful debugging tools with breakpoints, watch windows, call stacks, and immediate windows.
3. Designer Tools: Visual designers for GUI development, including Windows Forms, WPF (Windows Presentation Foundation), and web development (ASP.NET).
4. Integrated Source Control: Built-in support for version control systems like Git and TFVC (Team Foundation Version Control).
5. Testing Tools: Unit testing frameworks and tools for automated testing, including MSTest, NUnit, and xUnit.
6. Project Templates: A variety of project templates for different types of applications, including web, desktop, mobile, and cloud.
7. Extensions and Customization: A rich ecosystem of extensions available through the Visual Studio Marketplace, allowing customization and addition of new features.
8. Team Collaboration: Integration with Azure DevOps and GitHub for collaborative development, continuous integration, and deployment.
9. Performance Profiling: Tools for performance profiling, memory analysis, and diagnosing application performance issues.
10. Cloud Development: Tools for developing cloud applications, with support for Azure services and integration.

Visual Studio vs. Visual Studio Code
Visual Studio and Visual Studio Code (VS Code) are both development tools from Microsoft, but they serve different purposes and have different feature sets.

Visual Studio Code (VS Code)
Visual Studio Code is a lightweight, open-source code editor designed for a fast and streamlined development experience. It is highly customizable and supports a wide range of programming languages through extensions.

Key Differences
Purpose:
Visual Studio: A full-featured IDE designed for large-scale, enterprise-level development with comprehensive tools for project management, debugging, and deployment.
Visual Studio Code: A lightweight, extensible code editor aimed at providing a fast, efficient coding experience with essential development tools.

Performance:
Visual Studio: More resource-intensive due to its extensive features and capabilities.
Visual Studio Code: Designed to be lightweight and fast, making it suitable for quick edits and smaller projects.

Installation and Setup:
Visual Studio: Requires a larger installation and setup process, often tailored to specific development needs.
Visual Studio Code: Quick to install and set up, with a minimal initial footprint that can be extended through plugins.

Extensibility:
Visual Studio: Supports extensions but also comes with many built-in features out of the box.
Visual Studio Code: Relies heavily on extensions from the VS Code Marketplace to add functionality, allowing for a highly customizable environment.

Debugging and Testing:
Visual Studio: Advanced debugging and testing tools integrated into the IDE, supporting a wide range of testing frameworks and diagnostics.
Visual Studio Code: Basic debugging capabilities with extensions available to enhance testing and debugging features.

Project Types and Templates:
Visual Studio: Extensive project templates for different application types, including web, desktop, mobile, and cloud applications.
Visual Studio Code: No built-in project templates, but supports various project structures through extensions and custom configurations.

Platform Support:
Visual Studio: Primarily focused on Windows development, with some support for cross-platform development through Xamarin and .NET Core.
Visual Studio Code: Cross-platform support for Windows, macOS, and Linux, making it a versatile choice for developers on different operating systems.

Integrating GitHub with Visual Studio:
Describe the steps to integrate a GitHub repository with Visual Studio. How does this integration enhance the development workflow?
Integrating a GitHub repository with Visual Studio enhances the development workflow by streamlining version control operations, enabling seamless collaboration, and providing a unified development environment.

How Integration Enhances the Development Workflow
Streamlined Version Control:
Visual Studio provides a unified interface for Git operations, such as commit, push, pull, and branch management, reducing context switching and improving productivity.

Seamless Collaboration:
Integrated GitHub support makes it easy to collaborate with team members by creating and reviewing pull requests directly within Visual Studio.

Enhanced Code Reviews:
The pull request workflow within Visual Studio allows for inline commenting and code reviews, facilitating better communication and code quality.

Efficient Branch Management:
Visual Studio simplifies branch creation, switching, and merging, making it easier to manage feature development and bug fixes.

Automated Workflows:
Integration with GitHub Actions allows for automated CI/CD pipelines, ensuring that code changes are tested and deployed efficiently.

Centralized Development Environment:
Having source control, code editing, debugging, and deployment tools in one place improves efficiency and reduces the need to switch between different applications.

Access to GitHub Features:
Direct access to GitHub issues, pull requests, and repositories from within Visual Studio enhances the overall development experience by integrating project management and code hosting.

Example Workflow
1. Clone Repository: Clone an existing GitHub repository into Visual Studio.
2. Create Feature Branch: Create a new branch for a feature or bug fix.
3. Develop and Commit: Make changes, test locally, and commit changes to the feature branch.
4. Push to GitHub: Push the feature branch to the remote repository on GitHub.
5. Create Pull Request: Create a pull request for the feature branch and request a code review.
6. Review and Merge: Review the pull request, discuss changes, and merge it into the main branch once approved.
7. Pull Latest Changes: Pull the latest changes from the main branch to keep your local repository up to date.

Debugging in Visual Studio:
Explain the debugging tools available in Visual Studio. How can developers use these tools to identify and fix issues in their code?
Visual Studio provides a comprehensive set of debugging tools that help developers identify and fix issues in their code. These tools include breakpoints, watch windows, call stacks, immediate windows, and more. Here’s an overview of the key debugging tools available in Visual Studio and how developers can use them effectively:
1. Breakpoints
Breakpoints allow developers to pause the execution of their application at specific lines of code, which helps in examining the state of the application at those points.
Setting Breakpoints: Click in the margin next to a line of code or press F9 to toggle a breakpoint.
Conditional Breakpoints: Right-click on a breakpoint and choose "Conditions" to specify conditions under which the breakpoint should be hit.
Function Breakpoints: Set breakpoints on functions instead of specific lines by using the "New Breakpoint" dialog.
2. Watch Window
The Watch Window allows developers to monitor the values of variables and expressions as the application runs.
Adding Variables: Right-click a variable and select "Add to Watch" or type an expression directly in the Watch window.
Editing Values: Modify the values of variables while debugging to test different scenarios.
3. Call Stack
The Call Stack window shows the sequence of function calls that led to the current point in the program.
Navigating the Call Stack: Double-click on a function name in the Call Stack window to navigate to that point in the code.
Examining Frames: Inspect the state of each function in the call stack to understand how the current execution state was reached.
4. Locals and Autos Windows
Locals Window: Displays all the local variables in the current scope.
Autos Window: Shows variables used in the current line of code and the preceding line.
These windows automatically update as you step through the code, making it easy to track changes in variable values.
5. Immediate Window
The Immediate Window allows developers to interact with the application by executing code and evaluating expressions on the fly.
Evaluating Expressions: Type an expression and press Enter to see its value.
Executing Commands: Run commands and see their effects immediately.
6. Output Window
The Output Window displays various messages from the debugging session, such as debug messages, build output, and error messages.
Filtering Output: Use filters to display only the messages relevant to your debugging session.
7. Diagnostic Tools
The Diagnostic Tools window provides performance and diagnostic information during a debugging session.
Timeline: View a timeline of events such as CPU usage, memory allocation, and I/O activity.
IntelliTrace: Capture detailed logs of the application’s execution to diagnose complex issues.
8. Exception Settings
Exception Settings allow developers to configure how the debugger handles exceptions.
Configuring Exceptions: Go to Debug > Windows > Exception Settings to specify which exceptions should break execution and which should be ignored.
First-Chance Exceptions: Enable first-chance exception notifications to break on exceptions as soon as they are thrown.
9. Data Tips
Data Tips are tooltips that appear when you hover over a variable during a debugging session.
Inspecting Variables: Hover over a variable to see its current value and type.
Pinning Data Tips: Pin a data tip to keep it visible while stepping through the code.

Using Debugging Tools to Identify and Fix Issues
Step-by-Step Debugging
1. Set Breakpoints: Start by setting breakpoints at key points in your code where you suspect issues might be occurring.
2. Start Debugging: Press F5 to start the debugging session. The application will run and pause at the first breakpoint.
3. Inspect Variables: Use the Locals, Autos, and Watch windows to inspect the values of variables at the breakpoint.
4. Step Through Code: Use F10 (Step Over), F11 (Step Into), and Shift+F11 (Step Out) to step through the code line by line.
5. Examine the Call Stack: Open the Call Stack window to see the sequence of function calls and navigate between them to understand the flow of execution.
6. Use the Immediate Window: Test different scenarios by evaluating expressions and executing code in the Immediate Window.
7. Monitor Output: Check the Output window for any debug messages, errors, or warnings that can provide insights into the issue.
8. Diagnose Performance Issues: Use the Diagnostic Tools window to identify performance bottlenecks or resource-intensive operations.
9. Handle Exceptions: Configure Exception Settings to break on specific exceptions and use the Call Stack and Locals windows to diagnose the cause.

Collaborative Development using GitHub and Visual Studio:
Discuss how GitHub and Visual Studio can be used together to support collaborative development. Provide a real-world example of a project that benefits from this integration.
GitHub and Visual Studio together provide a powerful environment for collaborative development, offering seamless integration of version control, project management, and coding tools. Here’s how these tools can be effectively used together to support collaborative development, along with a real-world example:

GitHub for Collaborative Development
GitHub serves as a centralized platform for version control and collaboration, offering features such as:
1. Code Hosting: Store and manage code repositories in the cloud.
2. Version Control: Track changes made by team members, revert to previous versions, and manage branches.
3. Pull Requests: Facilitate code reviews and discussions before merging changes into the main branch.
4. Issue Tracking: Manage and prioritize tasks, bugs, and feature requests using GitHub Issues.
5. Integration with CI/CD: Automate build and deployment pipelines using GitHub Actions.

Visual Studio Integration with GitHub
Visual Studio seamlessly integrates with GitHub to enhance the collaborative development process:
1. Cloning Repositories: Easily clone GitHub repositories directly into Visual Studio for local development.
2. Commit and Push: Commit changes locally and push them to GitHub repositories.
3. Pull and Sync: Fetch changes from remote repositories and synchronize local branches with GitHub.
4. Pull Requests and Code Reviews: Create, review, and manage pull requests directly from Visual Studio.
5. Issue Integration: Link GitHub issues to commits, branches, and pull requests, allowing for better traceability and project management.

Real-World Example: ASP.NET Core Web Application
Imagine a team of developers working on an ASP.NET Core web application using GitHub and Visual Studio. Here’s how they leverage these tools:

1. Project Setup: The project is initiated on GitHub, where team members can clone the repository into Visual Studio using the GitHub extension for Visual Studio.
2. Collaborative Development:
Developers work on different features or bug fixes in separate branches within Visual Studio.
They commit changes to their local branches and push them to corresponding branches on GitHub.

3. Code Reviews:
Before merging changes into the main branch (main), developers create pull requests from their feature branches on GitHub.
Team members review code changes, provide feedback, and discuss improvements directly within the GitHub interface or using Visual Studio’s pull request integration.

4. Continuous Integration and Deployment:
GitHub Actions are configured to automate build and test workflows whenever changes are pushed to the main branch or pull requests are submitted.
Visual Studio’s integration with GitHub Actions allows developers to monitor build statuses, review test results, and deploy changes to staging or production environments.

5. Issue Management:
Team members use GitHub Issues to track tasks, bugs, and feature requests.
Issues are linked to commits and pull requests in Visual Studio, providing a seamless workflow from issue identification to code implementation and review.

6. Version Control and Synchronization:
Visual Studio’s Git integration ensures that developers always have the latest changes from GitHub.
They can pull updates from the remote repository and resolve any merge conflicts directly within Visual Studio’s merge tool.

Benefits of Integration
1. Efficiency: Seamless integration between GitHub and Visual Studio reduces context switching and improves workflow efficiency.
2. Collaboration: Enables effective collaboration through pull requests, code reviews, and issue tracking.
3. Quality Assurance: Automated testing and deployment pipelines ensure code quality and consistency.
4. Traceability: Linking issues to code changes provides traceability and helps in understanding the context of each change.

Submission Guidelines:
Your answers should be well-structured, concise, and to the point.
Provide real-world examples or case studies wherever possible.
Cite any references or sources you use in your answers.
Submit your completed assignment by [due date].
