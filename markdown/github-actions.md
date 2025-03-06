---
title: 'Github Actions: 100 Lessons'
layout: default
---

# GitHub Actions: 0 to 100 in 100 Lessons

## Foundations (1-10)

**1. What is GitHub Actions**
GitHub Actions is an automation platform that enables you to build CI/CD workflows directly in your GitHub repository.

**2. Key Concepts**
Understand workflows, jobs, steps, actions, and runners - the basic building blocks of GitHub Actions.

**3. Workflow Files**
Introduction to YAML-based workflow files stored in the `.github/workflows` directory of your repository.

**4. Events and Triggers**
Learn about events that can trigger workflows: push, pull request, schedule, manual dispatch, etc.

**5. Your First Workflow**
Create a simple "Hello World" workflow that runs on push events.

**6. Workflow Syntax Basics**
Understand the basic structure of a workflow file: name, triggers, jobs, and steps.

**7. Jobs and Steps**
Learn how to organize workflows into jobs and steps for better structure.

**8. Using Actions**
Incorporate pre-built actions from the GitHub Marketplace to save development time.

**9. Understanding Runners**
Learn about GitHub-hosted runners and their environments (Ubuntu, Windows, macOS).

**10. Workflow Visualization**
Use GitHub's UI to visualize and debug workflow runs.

## Core Concepts (11-25)

**11. Environment Variables**
Set and use environment variables in your workflows.

**12. Secrets Management**
Store and use sensitive information using GitHub Secrets.

**13. Artifacts**
Upload and download artifacts between jobs in a workflow.

**14. Job Dependencies**
Configure jobs to run sequentially with the `needs` keyword.

**15. Matrix Builds**
Test across multiple configurations using matrix strategies.

**16. Conditional Execution**
Use conditional statements (`if`) to control when steps and jobs run.

**17. Timeouts and Cancellation**
Set timeouts and handle workflow cancellations gracefully.

**18. Workflow Commands**
Use workflow commands to set outputs, debug, and communicate with the runner.

**19. Context and Expressions**
Access contextual information using expressions like `${{ github.event_name }}`.

**20. Environment Files**
Use environment files for sharing variables between steps.

**21. Service Containers**
Set up additional services like databases for testing.

**22. Caching Dependencies**
Speed up workflows by caching dependencies between runs.

**23. Custom Actions (JavaScript)**
Create your first custom action using JavaScript.

**24. Custom Actions (Docker)**
Build Docker-based custom actions for more complex needs.

**25. Custom Actions (Composite)**
Combine multiple actions into a single reusable composite action.

## Practical CI/CD (26-45)

**26. Testing Node.js Applications**
Set up automated testing for Node.js applications.

**27. Testing Python Applications**
Configure workflows for Python testing and linting.

**28. Java CI Workflows**
Implement CI for Java applications with Maven or Gradle.

**29. .NET Core CI Pipelines**
Automate CI for .NET applications.

**30. Linting and Code Quality**
Integrate code quality tools into your workflows.

**31. Security Scanning**
Set up security scanning with CodeQL and other tools.

**32. Containerization with Docker**
Build and push Docker images in your workflows.

**33. Basic Deployment Workflows**
Create simple deployment workflows for web applications.

**34. AWS Deployments**
Configure deployments to AWS services.

**35. Azure Deployments**
Deploy applications to Azure services.

**36. Google Cloud Deployments**
Set up GCP deployment workflows.

**37. Heroku Deployments**
Automate deployments to Heroku.

**38. Serverless Deployments**
Deploy serverless functions to various cloud providers.

**39. Database Migrations**
Safely run database migrations in your CI/CD pipeline.

**40. Feature Branch Environments**
Set up dynamic environments for feature branches.

**41. Pull Request Reviews**
Automate parts of the PR review process.

**42. Release Management**
Automate creating releases and changelogs.

**43. Semantic Versioning**
Implement automated semantic versioning.

**44. Multi-Stage Deployments**
Configure staging, QA, and production deployment pipelines.

**45. Blue-Green Deployments**
Implement zero-downtime deployments with blue-green strategy.

## Advanced Techniques (46-70)

**46. Self-Hosted Runners**
Set up and manage your own runners for custom environments.

**47. Runner Groups and Labels**
Organize runners into groups and use labels for targeting.

**48. Runner Security Best Practices**
Secure your self-hosted runners against potential threats.

**49. Organization-Level Workflows**
Create reusable workflows at the organization level.

**50. Reusable Workflows**
Define and call reusable workflows to reduce duplication.

**51. Workflow Templates**
Create and use workflow templates for standardization.

**52. Complex Matrix Strategies**
Advanced matrix configurations with include and exclude patterns.

**53. Output Parameters**
Share data between jobs using outputs.

**54. Job Concurrency Control**
Manage concurrency to prevent race conditions.

**55. Advanced Caching Strategies**
Implement sophisticated caching for maximum performance.

**56. Path Filtering**
Trigger workflows based on specific file paths.

**57. Monorepo Strategies**
Configure efficient CI/CD in monorepo architectures.

**58. Multi-Repository Workflows**
Coordinate actions across multiple repositories.

**59. Repository Dispatch Events**
Trigger workflows from external events or other repositories.

**60. API-Triggered Workflows**
Use the GitHub API to trigger workflows programmatically.

**61. Workflow Run API**
Interact with workflow runs using the GitHub API.

**62. Approval Workflows**
Implement manual approval steps in your deployment process.

**63. Feature Flags Integration**
Connect workflows with feature flag systems.

**64. A/B Testing Automation**
Automate A/B test deployments and analysis.

**65. Canary Deployments**
Implement canary release patterns with GitHub Actions.

**66. Rollback Strategies**
Create automated rollback mechanisms for failed deployments.

**67. Cross-Platform Builds**
Build applications that work across multiple operating systems.

**68. Performance Testing Integration**
Automate performance testing in your CI/CD pipeline.

**69. Load Testing Workflows**
Implement load and stress testing as part of deployment validation.

**70. Custom Workflow Metrics**
Collect and analyze metrics from your workflows.

## Enterprise and Compliance (71-85)

**71. Compliance Automation**
Automate compliance checks and reporting.

**72. Policy as Code**
Implement policy as code using Actions.

**73. Audit Logging and Monitoring**
Set up comprehensive logging for all workflow activities.

**74. Cost Management**
Optimize workflows for cost efficiency.

**75. Rate Limit Handling**
Deal with GitHub API rate limits effectively.

**76. Timeout Optimization**
Optimize workflow timeouts for different scenarios.

**77. Scheduled Maintenance Workflows**
Implement automated maintenance tasks.

**78. Disaster Recovery**
Create disaster recovery plans for your CI/CD pipelines.

**79. High Availability Setup**
Configure redundancy in critical workflows.

**80. Credential Rotation**
Automate the rotation of secrets and credentials.

**81. Enterprise SSO Integration**
Configure GitHub Actions with enterprise SSO solutions.

**82. RBAC and Permissions**
Implement role-based access control for Actions.

**83. Environment Protection Rules**
Configure protection rules for deployment environments.

**84. Compliance Reporting**
Generate compliance reports automatically.

**85. GitHub Enterprise Server Integration**
Use Actions with GitHub Enterprise Server.

## Advanced Scenarios and Best Practices (86-100)

**86. Testing Actions Locally**
Test Actions locally before pushing to GitHub.

**87. Actions Development Workflow**
Establish a development workflow for custom actions.

**88. Versioning Custom Actions**
Implement proper versioning for your custom actions.

**89. Documentation Generation**
Automate documentation generation and publishing.

**90. Infrastructure as Code Integration**
Connect GitHub Actions with IaC tools like Terraform.

**91. GitOps Workflows**
Implement GitOps patterns with GitHub Actions.

**92. ChatOps Integration**
Connect workflows with chat platforms for notifications and control.

**93. Multi-Cloud Strategy**
Manage deployments across multiple cloud providers.

**94. Advanced Debugging Techniques**
Master debugging complex workflows and actions.

**95. Performance Optimization**
Fine-tune workflows for maximum performance.

**96. GitHub Actions Patterns and Anti-patterns**
Learn common patterns to follow and mistakes to avoid.

**97. Workflow Migration Strategies**
Migrate from other CI/CD systems to GitHub Actions.

**98. Governance at Scale**
Manage GitHub Actions across large organizations.

**99. Keeping Up with Actions Updates**
Strategies for staying current with GitHub Actions changes.

**100. Building a Center of Excellence**
Establish a GitHub Actions center of excellence in your organization.

---

# GitHub Actions: Lesson 1 - What is GitHub Actions

GitHub Actions is an automation platform integrated directly into GitHub repositories that allows you to build continuous integration and continuous delivery (CI/CD) workflows. Let's break down the key aspects:

## Core Concept

GitHub Actions allows you to automate tasks and processes directly within your GitHub repository. Instead of using external CI/CD tools, you can define workflows right alongside your code.

## Key Benefits

1. **Native Integration**: Built directly into GitHub, eliminating the need for third-party tools
2. **Simplified Setup**: Define workflows using YAML files stored in your repository
3. **Community-Powered**: Access thousands of pre-built actions from the GitHub Marketplace
4. **Free Tier**: Generous free tier for public repositories (2,000 minutes/month)
5. **Flexible**: Works with any language, platform, or cloud

## Primary Use Cases

- **Continuous Integration**: Automatically build and test code changes
- **Continuous Deployment**: Deploy applications automatically when changes are made
- **Code Quality**: Run linters, security scanners, and other quality checks
- **Repository Management**: Automate issues, PRs, and other GitHub features
- **Custom Automation**: Create custom workflows for your specific needs


## How It Works

GitHub Actions uses a simple event-driven model:

1. An event occurs (e.g., a push to a branch)
2. This triggers a workflow (defined in YAML)
3. The workflow runs one or more jobs on runners (virtual machines)
4. Each job executes a series of steps to complete the automation

In the next lesson, we'll explore the fundamental concepts that make up GitHub Actions workflows.

---

# GitHub Actions: Lesson 2 - Key Concepts

To effectively use GitHub Actions, you need to understand its fundamental building blocks:

## Workflows

A workflow is an automated procedure that you add to your repository. Workflows:

- Are defined in YAML files located in the `.github/workflows` directory
- Can be triggered by various events in your GitHub repository
- Contain one or more jobs that can run sequentially or in parallel
- Example: A workflow that builds and tests your code on every push


## Jobs

Jobs are sets of steps that execute on the same runner (virtual machine):

- Each job runs in a fresh instance of the runner environment
- By default, jobs run in parallel, but can be configured to run sequentially
- Jobs can have dependencies on other jobs using the `needs` keyword
- Example: A "build" job followed by a "test" job that depends on the build


## Steps

Steps are individual tasks that can run commands or actions:

- Execute in order within their job
- Share the same runner filesystem (allowing file sharing between steps)
- Can be either shell commands or actions
- Example: A step that checks out code, followed by a step that installs dependencies


## Actions

Actions are reusable units of code that perform frequently repeated tasks:

- Can be created by you, the community, or GitHub
- Available in the GitHub Marketplace
- Simplify workflows by abstracting complex tasks
- Example: `actions/checkout@v3` which checks out your repository code


## Runners

Runners are the servers that execute your workflows:

- GitHub provides hosted runners with various operating systems
- You can also set up self-hosted runners in your own environment
- Each runner can run one job at a time
- Example: `ubuntu-latest`, `windows-latest`, or `macos-latest`

Understanding these core concepts provides the foundation for creating effective GitHub Actions workflows. In the next lesson, we'll explore workflow files in more detail.

---

# GitHub Actions: Lesson 3 - Workflow Files

Workflow files are the heart of GitHub Actions, defining what happens when your automation runs. Let's explore their structure and placement:

## File Location

Workflow files:

- Must be stored in the `.github/workflows` directory in your repository
- Use YAML syntax with either `.yml` or `.yaml` file extensions
- Can have any filename, though descriptive names are recommended
- Are automatically discovered and available for use once pushed to your repository


## Basic Structure

A minimal workflow file contains:

```yaml
name: My First Workflow

on: [push]

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - name: Say Hello
        run: echo "Hello, GitHub Actions!"
```


## Key Elements

1. **Name** (optional but recommended)
    - Appears in the Actions tab of your GitHub repository
    - Makes it easier to identify different workflows
2. **Triggers** (the `on:` section)
    - Defines what events will cause the workflow to run
    - Can be a single event or an array of events
    - May include filters to run only in specific conditions
3. **Jobs**
    - Contains all the jobs that will run in this workflow
    - Each job must have a unique ID (like `build` in the example)
    - Must specify which runner environment to use with `runs-on`
4. **Steps**
    - The sequence of tasks to be executed
    - Each step should have a name for clarity
    - Uses either `run:` for shell commands or `uses:` for actions

## Multiple Workflows

You can have multiple workflow files in your repository:

- Each operates independently
- Allows separation of concerns (e.g., one for testing, one for deployment)
- Can be triggered by the same events or different events


## Version Control

Workflow files are version-controlled just like your code:

- Changes are tracked through Git history
- Can be reviewed in pull requests
- Allows rollback to previous workflows if needed

In the next lesson, we'll dive deeper into events and triggers that start your workflows.

---

# GitHub Actions: Lesson 4 - Events and Triggers

GitHub Actions workflows are event-driven, meaning they start in response to specific events in your repository. Understanding these triggers is essential for creating effective automations.

## Common Trigger Events

### Code-Related Events

- **`push`**: When commits are pushed to matching branches
- **`pull_request`**: When a PR is opened, synchronized, or other PR actions
- **`create`**: When a branch or tag is created
- **`delete`**: When a branch or tag is deleted
- **`release`**: When a release is created, edited, published, etc.


### Scheduled Events

- **`schedule`**: Run workflows at scheduled times using cron syntax

```yaml
on:
  schedule:
    - cron: '0 0 * * *'  # Runs at midnight every day
```


### Manual Events

- **`workflow_dispatch`**: Manually trigger a workflow from the UI or API
- **`repository_dispatch`**: Trigger from external events via a webhook


## Event Filtering

You can filter events to run workflows only under specific conditions:

```yaml
on:
  push:
    branches: [main, 'release/**']
    tags: ['v*']
    paths:
      - 'src/**'
      - '!**.md'
  pull_request:
    types: [opened, synchronize]
    branches: [main]
```

This example:

- Runs on pushes to `main` or any branch starting with `release/`
- Runs on pushes of any tag starting with `v`
- Only runs when files in the `src` directory change (excluding markdown files)
- For PRs, only runs when they're opened or updated, and only for PRs to `main`


## Activity Types

Many events have specific activity types you can filter on:

```yaml
on:
  issues:
    types: [opened, labeled, milestoned]
```


## Multiple Events

You can trigger on multiple events with different configurations:

```yaml
on:
  push:
    branches: [main]
  pull_request:
    branches: [main]
  schedule:
    - cron: '0 0 * * *'
```

Understanding which events should trigger your workflows is crucial for building efficient CI/CD pipelines. In the next lesson, we'll create your first complete workflow.

---

# GitHub Actions: Lesson 5 - Your First Workflow

Let's create your first practical GitHub Actions workflow. We'll build a simple workflow that verifies your code when you push changes.

## Step 1: Create the Workflow File

In your repository, create a new file at `.github/workflows/first-workflow.yml` with the following content:

```yaml
name: First GitHub Action

on:
  push:
    branches: [ main ]
  pull_request:
    branches: [ main ]

jobs:
  build-and-test:
    runs-on: ubuntu-latest
    
    steps:
      - name: Check out repository code
        uses: actions/checkout@v3
        
      - name: List files in the repository
        run: |
          ls -la
          echo "Repository contents listed above"
          
      - name: Echo environment information
        run: |
          echo "Running on ${{ runner.os }}"
          echo "GitHub event: ${{ github.event_name }}"
          
      - name: Simple test
        run: echo "Your workflow is working!"
```


## Step 2: Understand the Workflow

This workflow:

1. **Triggers**: Runs when code is pushed to the main branch or when a pull request targets the main branch
2. **Jobs**: Contains a single job named `build-and-test` running on the latest Ubuntu environment
3. **Steps**:
    - Checks out your repository code using the `actions/checkout` action
    - Lists the files in your repository
    - Prints information about the environment
    - Runs a simple test (just an echo command for now)

## Step 3: Commit and Push

Commit this file and push it to your repository:

```bash
git add .github/workflows/first-workflow.yml
git commit -m "Add first GitHub Actions workflow"
git push
```


## Step 4: View the Results

1. Navigate to your GitHub repository
2. Click the "Actions" tab at the top
3. You should see your workflow running (or completed if it's already finished)
4. Click on the workflow run to see details
5. Explore the logs for each step

## What You've Learned

- How to create a basic workflow file
- The structure of a GitHub Actions workflow
- How to use the checkout action to access your code
- How to run shell commands in your workflow
- How to view workflow results in the GitHub UI

This simple workflow gives you a foundation to build upon. In the next lesson, we'll explore more advanced workflow syntax.

---

# GitHub Actions: Lesson 6 - Workflow Syntax Basics

Understanding the core syntax of GitHub Actions workflow files is essential for creating effective automations. Let's break down the key components of a workflow file in more detail.

## Basic Workflow Structure

A complete workflow file typically includes these main sections:

```yaml
name: Workflow Name

on: [event1, event2]

env:
  GLOBAL_VAR: value

jobs:
  job_id:
    name: Human-Readable Job Name
    runs-on: ubuntu-latest
    env:
      JOB_VAR: value
    
    steps:
      - name: Step 1 - Check out code
        uses: actions/checkout@v3
      
      - name: Step 2 - Run a command
        run: echo "Hello world"
        env:
          STEP_VAR: value
```


## Key Elements Explained

### 1. Workflow Name

```yaml
name: Workflow Name
```

- Optional but recommended for identification
- Displayed in the GitHub Actions UI
- Should be descriptive of the workflow's purpose


### 2. Trigger Definition

```yaml
on: [push, pull_request]
```

- Specifies what events trigger the workflow
- Can be a simple list or a more complex configuration
- Required for every workflow


### 3. Environment Variables

```yaml
env:
  KEY: value
```

- Optional section for global environment variables
- Available to all jobs in the workflow
- Good for configuration shared across multiple jobs


### 4. Jobs Section

```yaml
jobs:
  job_id:
    # job configuration
```

- Contains all jobs to be executed
- Each job needs a unique ID (job_id)
- Jobs run in parallel by default


### 5. Job Configuration

```yaml
job_id:
  name: Descriptive Name
  runs-on: ubuntu-latest
```

- `name`: Optional human-readable name
- `runs-on`: Required specification of runner environment
- Can include other configurations like `needs`, `if`, etc.


### 6. Steps

```yaml
steps:
  - name: Step Name
    uses: action-name@version
    # or
    run: command
```

- Sequential tasks within a job
- Each step either:
    - Uses an action (`uses` key)
    - Runs shell commands (`run` key)
- Can include error handling, conditional execution, etc.


## YAML Syntax Tips

- Indentation is crucial - use spaces, not tabs
- Lists can be written in block form (with dashes) or inline form (with brackets)
- Multi-line strings can use the pipe character (`|`)
- Comments start with `#`

This foundation will help you understand and create workflows more effectively. In the next lesson, we'll explore jobs and steps in more detail.

---

# GitHub Actions: Lesson 7 - Jobs and Steps

Understanding how to organize your workflows into jobs and steps is crucial for creating efficient and maintainable automations.

## Jobs

Jobs are the main building blocks of a workflow and represent a discrete unit of work:

### Basic Job Structure

```yaml
jobs:
  build:
    name: Build Application
    runs-on: ubuntu-latest
    steps:
      # steps go here
      
  test:
    name: Test Application
    runs-on: windows-latest
    steps:
      # steps go here
```


### Key Job Properties

1. **Job ID**: A unique identifier for the job (e.g., `build`, `test`)
2. **Name**: A human-readable label (optional but recommended)
3. **Runner**: The environment where the job will execute (required)
4. **Job Dependencies**:

```yaml
test:
  needs: build
```

This ensures `test` only runs after `build` completes successfully

### Job Execution Flow

- By default, jobs run in parallel for efficiency
- Jobs with dependencies (`needs`) run sequentially
- If any job fails, dependent jobs are skipped
- A workflow succeeds only if all jobs succeed


## Steps

Steps are individual tasks within a job that execute in sequence:

### Types of Steps

1. **Run a command**:

```yaml
steps:
  - name: Install dependencies
    run: npm install
```

2. **Use an action**:

```yaml
steps:
  - name: Checkout code
    uses: actions/checkout@v3
```


### Step Properties

1. **Name**: A descriptive label (optional but recommended)
2. **ID**: A unique identifier for referencing the step later (optional)

```yaml
steps:
  - name: Set output
    id: set-output
    run: echo "::set-output name=result::success"
```

3. **Conditional Execution**:

```yaml
steps:
  - name: Run only on main branch
    if: github.ref == 'refs/heads/main'
    run: echo "This is the main branch"
```


### Step Execution

- Steps run sequentially in the order defined
- If a step fails, subsequent steps in that job are skipped by default
- You can modify this behavior with conditional execution
- All steps in a job share the same filesystem


## Practical Job Organization

Consider these patterns for organizing jobs effectively:

1. **Build → Test → Deploy** pattern:

```yaml
jobs:
  build:
    # build job configuration
  test:
    needs: build
    # test job configuration
  deploy:
    needs: [build, test]
    # deploy job configuration
```

2. **Parallel Testing** pattern:

```yaml
jobs:
  build:
    # build job configuration
  test-unit:
    needs: build
    # unit test configuration
  test-integration:
    needs: build
    # integration test configuration
  deploy:
    needs: [test-unit, test-integration]
    # deploy configuration
```


In the next lesson, we'll explore how to use pre-built actions from the GitHub Marketplace to enhance your workflows.

---

# GitHub Actions: Lesson 8 - Using Actions

Actions are reusable units of code that simplify your workflows by abstracting complex tasks. They're one of the most powerful features of GitHub Actions, allowing you to leverage work done by GitHub and the community.

## Types of Actions

There are three types of actions:

1. **JavaScript Actions**: Run directly on the runner
2. **Docker Container Actions**: Run in a Docker container
3. **Composite Actions**: Combine multiple steps into one action

## Using an Action in Your Workflow

The basic syntax for using an action:

```yaml
steps:
  - name: Step Name
    uses: owner/repo@version
    with:
      param1: value1
      param2: value2
```


### Example: Checkout Action

```yaml
steps:
  - name: Check out repository code
    uses: actions/checkout@v3
    with:
      fetch-depth: 0  # Fetch all history
```


## Common Official Actions

GitHub provides several official actions for common tasks:

1. **actions/checkout@v3**
    - Checks out your repository code
    - Usually the first step in most workflows
2. **actions/setup-node@v3**
    - Sets up a Node.js environment

```yaml
- uses: actions/setup-node@v3
  with:
    node-version: '16'
    cache: 'npm'
```

3. **actions/cache@v3**
    - Caches dependencies to speed up workflows

```yaml
- uses: actions/cache@v3
  with:
    path: ~/.npm
    key: ${{ runner.os }}-node-${{ hashFiles('**/package-lock.json') }}
```

4. **actions/upload-artifact@v3**
    - Stores files from your workflow to use between jobs

```yaml 
- uses: actions/upload-artifact@v3
  with:
    name: my-artifact
    path: dist/
```


## Finding Actions in the Marketplace

1. Visit [GitHub Marketplace](https://github.com/marketplace?type=actions)
2. Search for actions relevant to your needs
3. Review documentation, popularity, and maintenance status
4. Check for verified creator badges (blue checkmarks)

## Version Pinning

When using actions, you can specify the version in three ways:

1. **Major version** (`@v3`): Auto-updates to minor and patch versions
2. **Specific version** (`@v3.1.0`): Pins to an exact version for stability
3. **Commit SHA** (`@a1b2c3d`): Maximum stability but no updates
```yaml
# Major version - gets minor updates
- uses: actions/checkout@v3

# Exact version - more stable
- uses: actions/checkout@v3.5.2

# Commit SHA - most stable
- uses: actions/checkout@8e5e7e5ab8b370d6c329ec480221332ada58f12b
```


## Security Best Practices

1. Use trusted actions from verified creators when possible
2. Pin actions to specific versions or commit SHAs for critical workflows
3. Regularly review and update action versions for security fixes
4. Consider action permissions and access requirements

In the next lesson, we'll explore GitHub-hosted runners and their environments.

---

# GitHub Actions: Lesson 9 - Understanding Runners

Runners are the execution environments that run your GitHub Actions workflows. Understanding runner options is crucial for configuring workflows that meet your performance, security, and compatibility needs.

## GitHub-Hosted Runners

GitHub provides managed virtual machines that are automatically provisioned when a workflow runs:

### Available Runner Types

1. **Ubuntu Linux**:
    - `ubuntu-latest`, `ubuntu-22.04`, `ubuntu-20.04`
    - Most commonly used runner
    - Best for most open-source projects
2. **Windows**:
    - `windows-latest`, `windows-2022`, `windows-2019`
    - Use for Windows-specific builds and tests
3. **macOS**:
    - `macos-latest`, `macos-12`, `macos-11`
    - Use for iOS/macOS app development

### Specifying a Runner

```yaml
jobs:
  build:
    runs-on: ubuntu-latest
    # job steps
```


### GitHub-Hosted Runner Specifications

Each runner type includes:

- 2-core CPU (7-core for macOS)
- 7 GB RAM (14 GB for macOS)
- 14 GB SSD space
- Pre-installed software (Git, language runtimes, build tools)
- Fresh environment for each job execution


### Runner Images and Software

GitHub regularly updates runner images with the latest software. You can find detailed information about what's installed on each runner at:

- [Ubuntu](https://github.com/actions/runner-images/blob/main/images/linux/Ubuntu2204-Readme.md)
- [Windows](https://github.com/actions/runner-images/blob/main/images/win/Windows2022-Readme.md)
- [macOS](https://github.com/actions/runner-images/blob/main/images/macos/macos-12-Readme.md)


## Runner Usage Limits

GitHub-hosted runners have usage limits:

- **Execution time**: 6 hours per job
- **Queue time**: 24 hours per workflow
- **API requests**: 1,000 requests per hour per repository
- **Concurrent jobs**: Depends on your GitHub plan


## Using Multiple Runners

You can use different runners for different jobs:

```yaml
jobs:
  build-linux:
    runs-on: ubuntu-latest
    # job steps
    
  build-windows:
    runs-on: windows-latest
    # job steps
    
  build-mac:
    runs-on: macos-latest
    # job steps
```


## Matrix Strategy with Runners

Test on multiple runner environments using matrix strategy:

```yaml
jobs:
  test:
    runs-on: ${{ matrix.os }}
    strategy:
      matrix:
        os: [ubuntu-latest, windows-latest, macos-latest]
    steps:
      - uses: actions/checkout@v3
      - run: ./run-tests.sh
```


## Self-Hosted Runners (Preview)

GitHub also supports self-hosted runners that you manage yourself. We'll cover these in detail in a later lesson, but they're useful when:

- You need custom hardware
- You require specific software not available on GitHub-hosted runners
- You need to access private network resources
- You want to reuse the same runner environment

In the next lesson, we'll explore the GitHub Actions workflow visualization interface.

---

# GitHub Actions: Lesson 10 - Workflow Visualization

GitHub provides a rich, interactive UI for visualizing and debugging your workflow executions. Understanding this interface is essential for monitoring and troubleshooting your automation.

## Accessing Workflow Runs

1. Navigate to your GitHub repository
2. Click the "Actions" tab at the top
3. You'll see a list of all workflow runs, with the most recent at the top

## Workflow Run List

The main Actions page shows:

- **Workflow names**: Grouped by the workflow file name
- **Run status**: Indicated by icons (✅ success, ❌ failure, 🟡 in progress)
- **Branch or tag**: The branch/tag that triggered the workflow
- **Event type**: What triggered the run (push, pull request, etc.)
- **Run number**: Sequential identifier for each workflow execution
- **Timing**: When the workflow was initiated and how long it ran


## Detailed Run View

Click on any workflow run to see detailed information:

1. **Summary tab**:
    - Overall status and timing
    - Commit information
    - Artifacts and workflow file link
    - Re-run options
2. **Jobs section**:
    - Visual representation of all jobs and their dependencies
    - Status of each job (with color coding)
    - Duration of each job
3. **Job details**:
    - Click on a job to see step-by-step execution
    - Expandable logs for each step
    - Timing information for individual steps
    - Environment details

## Log Navigation

When viewing job logs:

- Each step is collapsible/expandable
- Search functionality to find specific text in logs
- Option to download complete logs
- Timestamps for each log line
- Annotations for warnings and errors


## Workflow Annotations

GitHub automatically adds annotations to your runs:

- **Errors**: Highlighted in red with details about failures
- **Warnings**: Highlighted in yellow for potential issues
- **Notices**: Informational messages about your workflow

These appear both in the logs and as summary information at the top of the run view.

## Workflow Controls

From the interface, you can:

- **Re-run** a workflow (all jobs or just failed jobs)
- **Cancel** a running workflow
- **View the workflow file** used for this run
- **Download artifacts** produced by the workflow
- **View raw logs** for detailed debugging


## Workflow Insights

The Actions tab also provides analytics:

1. Click on a specific workflow name (not a run)
2. You'll see a dashboard showing:
    - Success/failure rates over time
    - Execution time trends
    - Most frequent failures

## Practical Tips

- Use descriptive step names to make logs easier to understand
- Add debug information to important steps
- Use the job visualization to understand dependencies between jobs
- Check the annotations for quick identification of issues

Understanding this interface will help you monitor your workflows effectively and quickly diagnose any issues that arise. In the next lesson, we'll explore environment variables in GitHub Actions.

---

# GitHub Actions: Lesson 11 - Environment Variables

Environment variables allow you to store and reuse configuration information in your workflow. They provide a flexible way to pass data between steps and customize workflow behavior without modifying the workflow file.

## Default Environment Variables

GitHub Actions provides many built-in variables automatically:

```yaml
steps:
  - name: Print default environment variables
    run: |
      echo "Repository: $GITHUB_REPOSITORY"
      echo "Workflow: $GITHUB_WORKFLOW"
      echo "Ref: $GITHUB_REF"
      echo "SHA: $GITHUB_SHA"
      echo "Action: $GITHUB_ACTION"
      echo "Actor: $GITHUB_ACTOR"
```


### Commonly Used Default Variables

- `GITHUB_REPOSITORY`: Owner and repository name (e.g., `octocat/hello-world`)
- `GITHUB_WORKFLOW`: Name of the workflow
- `GITHUB_REF`: Branch or tag ref that triggered the workflow
- `GITHUB_SHA`: Commit SHA that triggered the workflow
- `GITHUB_ACTOR`: Username of the user that initiated the workflow
- `GITHUB_WORKSPACE`: Path to the repository on the runner
- `GITHUB_EVENT_NAME`: Name of the event that triggered the workflow
- `GITHUB_TOKEN`: A token for authentication (automatically provided)


## Setting Custom Environment Variables

You can set environment variables at three levels:

### 1. Workflow Level

Variables available to all jobs in the workflow:

```yaml
name: Environment Variables Demo

env:
  GLOBAL_VAR: "This is available to all jobs"

jobs:
  example-job:
    runs-on: ubuntu-latest
    steps:
      - name: Use workflow env var
        run: echo "Global variable: $GLOBAL_VAR"
```


### 2. Job Level

Variables available to all steps in a specific job:

```yaml
jobs:
  example-job:
    runs-on: ubuntu-latest
    env:
      JOB_VAR: "This is available to all steps in this job"
    steps:
      - name: Use job env var
        run: echo "Job variable: $JOB_VAR"
```


### 3. Step Level

Variables available only to a specific step:

```yaml
steps:
  - name: Step with its own env vars
    env:
      STEP_VAR: "This is only available in this step"
    run: echo "Step variable: $STEP_VAR"
```


## Setting Variables During Execution

You can set variables during workflow execution that are available to subsequent steps:

### For bash (Linux/macOS)

```yaml
steps:
  - name: Set environment variable
    run: echo "ACTION_STATE=yellow" >> $GITHUB_ENV
    
  - name: Use dynamically set variable
    run: echo "$ACTION_STATE" # Will output "yellow"
```


### For PowerShell (Windows)

```yaml
steps:
  - name: Set environment variable
    run: echo "ACTION_STATE=yellow" | Out-File -FilePath $env:GITHUB_ENV -Append
    
  - name: Use dynamically set variable
    run: echo "$env:ACTION_STATE" # Will output "yellow"
```


## Multiline Variables

For multiline values, use a delimiter:

```yaml
steps:
  - name: Set multiline env variable
    run: |
      echo "MULTI_LINE<<EOF" >> $GITHUB_ENV
      echo "Line 1" >> $GITHUB_ENV
      echo "Line 2" >> $GITHUB_ENV
      echo "Line 3" >> $GITHUB_ENV
      echo "EOF" >> $GITHUB_ENV
```


## Context Access to Variables

You can also access environment variables using expression contexts:

```yaml
steps:
  - name: Use env with expressions
    run: echo "${{ env.GLOBAL_VAR }}"
```

Environment variables provide a powerful way to make your workflows flexible and configurable. In the next lesson, we'll explore how to handle sensitive information using GitHub Secrets.

---

# GitHub Actions: Lesson 12 - Secrets Management

Secrets allow you to store sensitive information in your GitHub repository and use it in your workflows without exposing it in your code. This is essential for handling credentials, API tokens, and other confidential data.

## Types of Secrets

GitHub Actions supports several types of secrets:

1. **Repository Secrets**: Available to all workflows in a single repository
2. **Organization Secrets**: Available to workflows across multiple repositories in an organization
3. **Environment Secrets**: Available only to workflows running in a specific environment
4. **Dependabot Secrets**: Available only to Dependabot automated dependency updates

## Creating Repository Secrets

To create a repository secret:

1. Navigate to your repository on GitHub
2. Go to "Settings" > "Secrets and variables" > "Actions"
3. Click "New repository secret"
4. Enter a name (e.g., `API_TOKEN`) and value
5. Click "Add secret"

## Using Secrets in Workflows

Access secrets using the `secrets` context in your workflow file:

```yaml
jobs:
  deploy:
    runs-on: ubuntu-latest
    steps:
      - name: Deploy with API token
        run: ./deploy-script.sh
        env:
          API_TOKEN: ${{ secrets.API_TOKEN }}
```

Important notes:

- Secrets are encrypted and only exposed to the runner during execution
- Secret values are masked in logs (replaced with asterisks)
- Cannot use secrets directly in if conditions (use an intermediate step)


## Organization Secrets

For teams managing multiple repositories:

1. Go to your organization page on GitHub
2. Navigate to "Settings" > "Secrets and variables" > "Actions"
3. Click "New organization secret"
4. Enter name and value
5. Optionally restrict access to specific repositories
6. Click "Add secret"

Access them the same way as repository secrets:

```yaml
env:
  ORG_LEVEL_SECRET: ${{ secrets.ORG_LEVEL_SECRET }}
```


## Environment Secrets

For deployment-specific credentials:

1. Go to repository "Settings" > "Environments"
2. Create or select an environment
3. Under "Environment secrets", click "Add secret"
4. Enter name and value
5. Click "Add secret"

Access them in workflows with environment configured:

```yaml
jobs:
  deploy-production:
    runs-on: ubuntu-latest
    environment: production
    steps:
      - name: Deploy
        env:
          DEPLOY_KEY: ${{ secrets.DEPLOY_KEY }}
        run: ./deploy.sh
```


## Best Practices for Secrets

1. **Limit scope**: Use environment secrets when possible to limit exposure
2. **Rotate regularly**: Update secrets periodically, especially after team changes
3. **Avoid logging**: Never log secret values, even partially
4. **Minimize secrets usage**: Only use secrets where absolutely necessary
5. **Review access**: Regularly audit who has access to modify secrets

## Security Considerations

- Secrets are not passed to workflows triggered by pull requests from forks
- Third-party actions can potentially access your secrets, so only use trusted actions
- Secrets have a size limit of 64 KB
- Secret names can only contain alphanumeric characters and underscores

Secrets management is critical for workflow security. In the next lesson, we'll explore how to use artifacts to share data between jobs in a workflow.

---

# GitHub Actions: Lesson 13 - Artifacts

Artifacts allow you to persist data after a workflow run has completed and share data between jobs in a workflow. They're essential for passing build outputs, test results, and logs between different stages of your CI/CD pipeline.

## What Are Artifacts?

Artifacts are files or collections of files produced during a workflow run. Examples include:

- Compiled applications
- Build packages (JAR, WAR, ZIP)
- Test reports
- Log files
- Documentation


## Uploading Artifacts

Use the `actions/upload-artifact` action to save files from your workflow:

```yaml
steps:
  - name: Build application
    run: npm run build
    
  - name: Upload build artifacts
    uses: actions/upload-artifact@v3
    with:
      name: build-files
      path: dist/
      retention-days: 5  # Optional, defaults to 90 days
```

Key parameters:

- `name`: Identifier for the artifact (used when downloading)
- `path`: File, directory, or glob pattern of what to upload
- `retention-days`: How long to keep the artifact (1-90 days)


## Downloading Artifacts

Use the `actions/download-artifact` action to retrieve artifacts:

```yaml
jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - name: Build
        run: make build
      - name: Upload
        uses: actions/upload-artifact@v3
        with:
          name: build-output
          path: build/
          
  deploy:
    needs: build
    runs-on: ubuntu-latest
    steps:
      - name: Download build artifacts
        uses: actions/download-artifact@v3
        with:
          name: build-output
          path: build-output/
      
      - name: Deploy
        run: ./deploy.sh build-output/
```


## Artifact Configuration Options

### Uploading Multiple Directories

```yaml
- uses: actions/upload-artifact@v3
  with:
    name: all-assets
    path: |
      dist
      build/reports
      coverage
```


### Using Wildcards

```yaml
- uses: actions/upload-artifact@v3
  with:
    name: test-results
    path: test-results/**/*.xml
```


### Excluding Files

```yaml
- uses: actions/upload-artifact@v3
  with:
    name: logs
    path: |
      logs/
      !logs/**/*.tmp
```


## Accessing Artifacts via the UI

1. Navigate to your GitHub repository
2. Click the "Actions" tab
3. Select a workflow run
4. Scroll down to the "Artifacts" section
5. Download artifacts directly from the UI

## Practical Use Cases

1. **Build and Deploy**:
    - Job 1: Build the application and upload the compiled assets
    - Job 2: Download those assets and deploy them
2. **Test Reports**:
    - Upload test reports as artifacts for review even if tests fail
    - Keep a history of test outputs for debugging
3. **Cross-Platform Compilation**:
    - Build on multiple platforms
    - Gather all builds as artifacts for release
4. **Documentation**:
    - Generate documentation in one job
    - Publish it to GitHub Pages in another job

## Artifact Limitations

- Maximum size: 2GB per artifact
- Maximum total size: 5GB for all artifacts in a workflow
- Storage duration: Default 90 days (configurable)

Artifacts provide a robust way to share files between jobs and preserve outputs from your workflows. In the next lesson, we'll explore how to create more complex workflows using job dependencies.

---

# GitHub Actions: Lesson 14 - Job Dependencies

Creating workflows with multiple jobs that depend on each other allows you to build complex automation pipelines while maintaining organization and clarity. Job dependencies help you control execution flow and ensure jobs run in the correct order.

## Basic Job Dependencies

Use the `needs` keyword to specify that a job depends on the completion of one or more other jobs:

```yaml
jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      - run: ./build.sh
      
  test:
    needs: build
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      - run: ./test.sh
      
  deploy:
    needs: [build, test]
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      - run: ./deploy.sh
```

In this example:

- `test` will only start after `build` successfully completes
- `deploy` will only start after both `build` and `test` successfully complete
- If `build` fails, both `test` and `deploy` are skipped
- If `test` fails, `deploy` is skipped


## Creating Job Dependency Chains

You can create chains of dependent jobs:

```yaml
jobs:
  job1:
    # steps
    
  job2:
    needs: job1
    # steps
    
  job3:
    needs: job2
    # steps
    
  job4:
    needs: job3
    # steps
```


## Parallel and Sequential Job Combinations

You can design complex workflows with both parallel and sequential jobs:

```yaml
jobs:
  initial-setup:
    # steps
    
  parallel-job-a:
    needs: initial-setup
    # steps
    
  parallel-job-b:
    needs: initial-setup
    # steps
    
  parallel-job-c:
    needs: initial-setup
    # steps
    
  final-job:
    needs: [parallel-job-a, parallel-job-b, parallel-job-c]
    # steps
```

In this pattern:

1. `initial-setup` runs first
2. After it completes, `parallel-job-a`, `parallel-job-b`, and `parallel-job-c` all run in parallel
3. Finally, `final-job` runs after all the parallel jobs complete

## Passing Data Between Dependent Jobs

When using job dependencies, you'll often need to share data between jobs. This requires artifacts:

```yaml
jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      - run: npm run build
      - uses: actions/upload-artifact@v3
        with:
          name: build-output
          path: dist/
          
  deploy:
    needs: build
    runs-on: ubuntu-latest
    steps:
      - uses: actions/download-artifact@v3
        with:
          name: build-output
          path: dist/
      - run: ./deploy.sh
```


## Outputs and Job Dependencies

You can also pass small pieces of data between jobs using outputs:

```yaml
jobs:
  job1:
    runs-on: ubuntu-latest
    outputs:
      output1: ${{ steps.step1.outputs.test }}
    steps:
      - id: step1
        run: echo "test=hello" >> $GITHUB_OUTPUT
        
  job2:
    needs: job1
    runs-on: ubuntu-latest
    steps:
      - run: echo ${{ needs.job1.outputs.output1 }}  # Prints "hello"
```


## Conditional Job Execution

You can conditionally run dependent jobs using the `if` keyword:

```yaml
jobs:
  build:
    runs-on: ubuntu-latest
    outputs:
      should_deploy: ${{ steps.check.outputs.deploy }}
    steps:
      - id: check
        run: |
          if [[ "${{ github.ref }}" == "refs/heads/main" ]]; then
            echo "deploy=true" >> $GITHUB_OUTPUT
          else
            echo "deploy=false" >> $GITHUB_OUTPUT
          fi
          
  deploy:
    needs: build
    if: ${{ needs.build.outputs.should_deploy == 'true' }}
    runs-on: ubuntu-latest
    steps:
      - run: echo "Deploying..."
```

Job dependencies are essential for creating structured, efficient workflows that properly sequence your automation tasks. In the next lesson, we'll explore matrix builds for testing across multiple configurations.

---

# GitHub Actions: Lesson 15 - Matrix Builds

Matrix builds allow you to run a job across multiple configurations, such as different operating systems, language versions, or browser environments. This is especially useful for testing applications across various environments with minimal workflow configuration.

## Basic Matrix Syntax

The basic syntax for a matrix build uses the `strategy` and `matrix` keywords:

```yaml
jobs:
  test:
    runs-on: ${{ matrix.os }}
    strategy:
      matrix:
        os: [ubuntu-latest, windows-latest, macos-latest]
        node-version: [14, 16, 18]
    
    steps:
      - uses: actions/checkout@v3
      
      - name: Set up Node.js ${{ matrix.node-version }}
        uses: actions/setup-node@v3
        with:
          node-version: ${{ matrix.node-version }}
          
      - name: Install dependencies
        run: npm ci
        
      - name: Run tests
        run: npm test
```

This example creates a matrix of 9 jobs (3 operating systems × 3 Node.js versions), each running in parallel with its own configuration.

## Accessing Matrix Values

Matrix values are available as context variables:

```yaml
steps:
  - name: Log matrix values
    run: |
      echo "OS: ${{ matrix.os }}"
      echo "Node version: ${{ matrix.node-version }}"
```


## Including Additional Variables

You can include other variables in your matrix:

```yaml
strategy:
  matrix:
    os: [ubuntu-latest, windows-latest]
    node-version: [14, 16, 18]
    environment: [development, staging]
    include:
      - os: macos-latest
        node-version: 18
        environment: production
```


## Excluding Specific Combinations

You can exclude specific combinations from your matrix:

```yaml
strategy:
  matrix:
    os: [ubuntu-latest, windows-latest, macos-latest]
    node-version: [14, 16, 18]
    exclude:
      - os: macos-latest
        node-version: 14
      - os: windows-latest
        node-version: 16
```


## Adding Custom Variables to Specific Combinations

You can add extra variables to specific combinations using `include`:

```yaml
strategy:
  matrix:
    os: [ubuntu-latest, windows-latest]
    node-version: [14, 16]
    include:
      - os: ubuntu-latest
        node-version: 16
        experimental: true
        coverage: true
```


## Fail-Fast Behavior

By default, a matrix build will stop all jobs if any job fails. You can change this behavior:

```yaml
strategy:
  fail-fast: false  # Continue running other jobs even if one fails
  matrix:
    # matrix configuration
```


## Maximum Parallel Jobs

You can limit how many jobs run in parallel:

```yaml
strategy:
  max-parallel: 2  # Run at most 2 jobs at once
  matrix:
    # matrix configuration
```


## Dynamic Matrix Generation

For advanced scenarios, you can generate matrix values dynamically:

```yaml
jobs:
  generate-matrix:
    runs-on: ubuntu-latest
    outputs:
      matrix: ${{ steps.set-matrix.outputs.matrix }}
    steps:
      - id: set-matrix
        run: |
          echo "matrix=$(cat config.json)" >> $GITHUB_OUTPUT
          
  test:
    needs: generate-matrix
    runs-on: ubuntu-latest
    strategy:
      matrix: ${{ fromJson(needs.generate-matrix.outputs.matrix) }}
    steps:
      # Test steps
```


## Practical Matrix Examples

### Testing Multiple Language Versions

```yaml
strategy:
  matrix:
    python-version: [3.7, 3.8, 3.9, 3.10]
```


### Browser Testing

```yaml
strategy:
  matrix:
    browser: [chrome, firefox, safari, edge]
```


### Database Compatibility

```yaml
strategy:
  matrix:
    database: [mysql, postgres, sqlite, mongodb]
    db-version: [latest, previous]
```

Matrix builds dramatically reduce the amount of configuration needed to test across multiple environments, making your workflows more maintainable and comprehensive. In the next lesson, we'll explore conditional execution to control when steps and jobs run.

---

# GitHub Actions: Lesson 16 - Conditional Execution

Conditional execution allows you to control when jobs and steps run based on specific conditions. This makes your workflows more dynamic and efficient by only running necessary tasks.

## Basic Conditional Syntax

Use the `if` keyword to specify conditions for steps or jobs:

```yaml
steps:
  - name: Run only on main branch
    if: github.ref == 'refs/heads/main'
    run: echo "This is the main branch"
```


## Context and Expression Syntax

Conditions use expressions with the following syntax:

- Enclosed in `${{ }}` when used in property values
- Used directly with the `if` keyword

```yaml
if: ${{ github.event_name == 'push' }}
# or simply 
if: github.event_name == 'push'
```


## Common Contexts for Conditions

1. **`github` context**:

```yaml
if: github.event_name == 'pull_request'
if: github.ref == 'refs/heads/main'
if: github.repository == 'octocat/repo-name'
```

2. **`env` context**:

```yaml
if: env.ENVIRONMENT == 'production'
```

3. **`job` context**:

```yaml
if: job.status == 'success'
```


## Conditional Operators

GitHub Actions supports various operators in conditions:

- Comparison: `==`, `!=`, `>`, `<`, `>=`, `<=`
- Logical: `&&` (and), `||` (or), `!` (not)
- Pattern matching: `contains()`, `startsWith()`, `endsWith()`


## Practical Conditional Examples

### Branch-Specific Steps

```yaml
steps:
  - name: Deploy to production
    if: github.ref == 'refs/heads/main'
    run: ./deploy-prod.sh
    
  - name: Deploy to staging
    if: github.ref == 'refs/heads/staging'
    run: ./deploy-staging.sh
```


### Event-Specific Jobs

```yaml
jobs:
  test:
    runs-on: ubuntu-latest
    # Always run tests
    steps:
      - uses: actions/checkout@v3
      - run: npm test
      
  deploy:
    runs-on: ubuntu-latest
    needs: test
    # Only deploy on push to main, not on pull requests
    if: github.event_name == 'push' && github.ref == 'refs/heads/main'
    steps:
      - uses: actions/checkout@v3
      - run: ./deploy.sh
```


### Complex Conditions

```yaml
steps:
  - name: Complex condition example
    if: >-
      (github.event_name == 'push' || github.event_name == 'workflow_dispatch') &&
      (github.ref == 'refs/heads/main' || github.ref == 'refs/heads/staging') &&
      !contains(github.event.head_commit.message, '[skip ci]')
    run: echo "Running important step"
```


## Conditional Job Execution Based on Previous Job

```yaml
jobs:
  build:
    runs-on: ubuntu-latest
    outputs:
      build_status: ${{ steps.status.outputs.status }}
    steps:
      - id: status
        run: echo "status=success" >> $GITHUB_OUTPUT
        
  deploy:
    needs: build
    if: needs.build.outputs.build_status == 'success'
    runs-on: ubuntu-latest
    steps:
      - run: ./deploy.sh
```

Conditional execution makes your workflows smarter and more efficient by running only what's needed in each situation. In the next lesson, we'll explore timeouts and cancellation.

---

# GitHub Actions: Lesson 17 - Timeouts and Cancellation

GitHub Actions workflows and jobs can sometimes run longer than expected or get stuck. Timeouts and cancellation strategies help you manage these scenarios and prevent wasted resources.

## Workflow Timeouts

By default, workflows have a maximum runtime of 72 hours (6 hours for GitHub-hosted runners). You can set a custom timeout at the workflow level:

```yaml
name: My Workflow

on: push

jobs:
  my-job:
    runs-on: ubuntu-latest
    # workflow steps here

# Set a workflow-level timeout (in minutes)
timeout-minutes: 60
```


## Job Timeouts

You can set timeouts for individual jobs:

```yaml
jobs:
  build:
    runs-on: ubuntu-latest
    timeout-minutes: 30  # This job will timeout after 30 minutes
    steps:
      - uses: actions/checkout@v3
      - run: ./long-running-script.sh
```


## Step Timeouts

For more granular control, you can implement timeouts at the step level using timeout commands:

### Bash (Linux/macOS)

```yaml
steps:
  - name: Step with timeout
    run: |
      timeout 5m ./potentially-long-script.sh
      # or
      ./potentially-long-script.sh & PID=$! && (sleep 300; kill $PID) & TIMER=$! && wait $PID && kill $TIMER
```


### PowerShell (Windows)

```yaml
steps:
  - name: Step with timeout
    run: |
      Start-Process -FilePath ".\potentially-long-script.ps1" -Wait -TimeoutSec 300
```


## Handling Cancellation

Workflows can be cancelled manually or automatically (when a newer workflow run is triggered). You can add cleanup steps that run even after cancellation:

```yaml
jobs:
  job1:
    runs-on: ubuntu-latest
    steps:
      - name: Checkout
        uses: actions/checkout@v3
        
      - name: Main task
        run: ./main-task.sh
        
      - name: Cleanup
        if: ${{ always() }}
        run: ./cleanup.sh
```

The `always()` condition ensures the cleanup step runs regardless of whether the job was cancelled or failed.

## Cancellation Hooks

For more complex scenarios, you can implement cancellation hooks with `trap` (bash) or similar mechanisms:

```yaml
steps:
  - name: Task with cancellation hook
    run: |
      function cleanup {
        echo "Performing cleanup..."
        # Cleanup actions here
      }
      
      # Set up trap to catch termination signals
      trap cleanup EXIT
      
      # Main script
      ./main-script.sh
```


## Best Practices

1. **Set appropriate timeouts**: Choose timeout values that reflect the expected runtime with some margin
2. **Add cleanup steps**: Ensure resources are properly released on cancellation
3. **Implement graceful shutdowns**: Design scripts to handle termination signals
4. **Use checkpoints**: For long-running jobs, implement checkpointing to resume progress

Proper timeout and cancellation handling ensures your workflows are resilient and don't waste resources when things go wrong. In the next lesson, we'll explore workflow commands for communication with the runner.

---

# GitHub Actions: Lesson 18 - Workflow Commands

Workflow commands are special instructions that allow your workflow steps to communicate with the GitHub Actions runner. They provide a way to control the workflow execution, set outputs, create annotations, and more.

## Basic Workflow Command Syntax

Workflow commands use a special echo syntax:

```
echo "::command name parameter1=value,parameter2=value::command value"
```

For modern GitHub Actions, many commands now use environment files instead:

```bash
echo "name=value" >> $GITHUB_OUTPUT
```


## Essential Workflow Commands

### Setting Outputs

To set an output for a step (that can be used in later steps or jobs):

```bash
# For bash (Linux/macOS)
echo "result=success" >> $GITHUB_OUTPUT

# For PowerShell (Windows)
"result=success" | Out-File -FilePath $env:GITHUB_OUTPUT -Append
```

Access in later steps:

```yaml
steps:
  - id: set-result
    run: echo "result=success" >> $GITHUB_OUTPUT
    
  - run: echo "The result was ${{ steps.set-result.outputs.result }}"
```


### Setting Environment Variables

To set an environment variable for subsequent steps:

```bash
# For bash
echo "CACHE_KEY=node-deps-${{ hashFiles('**/package-lock.json') }}" >> $GITHUB_ENV

# For PowerShell
"CACHE_KEY=node-deps-${{ hashFiles('**/package-lock.json') }}" | Out-File -FilePath $env:GITHUB_ENV -Append
```


### Adding Path

To add a directory to the system PATH:

```bash
# For bash
echo "$HOME/.local/bin" >> $GITHUB_PATH

# For PowerShell
"$env:HOME/.local/bin" | Out-File -FilePath $env:GITHUB_PATH -Append
```


### Creating Annotations

To create warning and error annotations that appear in the GitHub UI:

```bash
# Warning
echo "::warning file=app.js,line=10,col=5::Missing semicolon"

# Error
echo "::error file=app.js,line=15,col=8::Syntax error"

# Notice
echo "::notice file=app.js,line=20,col=1::Consider refactoring this function"
```


### Masking Values

To prevent a value from appearing in logs:

```bash
echo "::add-mask::secret-value-to-hide"
```


### Setting Debug Logs

To enable additional debug logging:

```bash
echo "::debug::This is a debug message"
```


## Group Commands

To create collapsible groups in the log output:

```bash
echo "::group::My Group Title"
echo "This content will be in the group"
echo "Multiple lines can be included"
echo "::endgroup::"
```


## Workflow Command File Environment

Modern GitHub Actions uses these environment files:

- `$GITHUB_OUTPUT`: For setting outputs
- `$GITHUB_ENV`: For setting environment variables
- `$GITHUB_PATH`: For modifying PATH
- `$GITHUB_STEP_SUMMARY`: For adding content to the job summary

Workflow commands provide powerful ways to control workflow execution and improve the visibility of your workflow results. In the next lesson, we'll explore contexts and expressions for accessing data within workflows.

---

# GitHub Actions: Lesson 19 - Context and Expressions

Context and expressions in GitHub Actions allow you to access and manipulate data during workflow execution. They provide a way to reference information about the workflow, jobs, steps, and GitHub environment.

## Understanding Contexts

Contexts are collections of variables containing information about the workflow run. They're accessed using the expression syntax:

```yaml
${{ context.property.subproperty }}
```


## Key Available Contexts

1. **`github` Context**: Information about the workflow and event that triggered it

```yaml
${{ github.actor }}       # Person who triggered the workflow
${{ github.repository }}  # Repository name with owner (e.g., octocat/repo)
${{ github.ref }}         # Branch or tag ref that triggered the workflow
${{ github.sha }}         # Commit SHA that triggered the workflow
${{ github.event_name }}  # Name of the event that triggered the workflow
${{ github.event }}       # Full event webhook payload
```

2. **`env` Context**: Environment variables set in the workflow

```yaml
${{ env.MY_VARIABLE }}
```

3. **`job` Context**: Information about the currently running job

```yaml
${{ job.status }}  # Current status of the job
```

4. **`steps` Context**: Information about steps that have already run in the job

```yaml
${{ steps.step_id.outputs.output_name }}
```

5. **`runner` Context**: Information about the runner executing the job

```yaml
${{ runner.os }}          # Operating system (Linux, Windows, macOS)
${{ runner.temp }}        # Temp directory path on the runner
${{ runner.workspace }}   # Workspace directory path on the runner
```

6. **`needs` Context**: Outputs from jobs that are dependencies of the current job

```yaml
${{ needs.job_id.outputs.output_name }}
```


## Expression Syntax

Expressions can include:

1. **Literals**:
    - String: `'hello'`
    - Number: `123.45`
    - Boolean: `true` or `false`
    - Null: `null`
2. **Operators**:
    - Comparison: `==`, `!=`, `>`, `<`, `>=`, `<=`
    - Logical: `&&`, `||`, `!`
3. **Functions**:

```yaml
${{ contains('hello', 'll') }}        # true
${{ startsWith('hello', 'he') }}      # true
${{ endsWith('hello', 'lo') }}        # true
${{ format('Hello {0}!', 'World') }}  # 'Hello World!'
${{ join(['hello', 'world'], ' ') }}  # 'hello world'
```


## Using Expressions in Workflows

Expressions can be used in many parts of a workflow:

```yaml
name: Expression Examples

on: push

env:
  GREETING: Hello
  
jobs:
  example:
    runs-on: ${{ github.event_name == 'push' && 'ubuntu-latest' || 'windows-latest' }}
    
    if: ${{ github.ref == 'refs/heads/main' }}
    
    steps:
      - name: Output greeting
        run: echo "${{ env.GREETING }}, ${{ github.actor }}!"
        
      - name: Set output
        id: set-output
        run: echo "result=success" >> $GITHUB_OUTPUT
        
      - name: Use output
        run: echo "Previous step output was ${{ steps.set-output.outputs.result }}"
        
      - name: Conditional step
        if: ${{ success() && github.event_name == 'push' }}
        run: echo "This only runs on successful push events"
```


## Special Functions

GitHub Actions provides special functions for expressions:

- `success()`: Returns true when none of the previous steps have failed
- `always()`: Always returns true, even when cancelled
- `cancelled()`: Returns true if the workflow was cancelled
- `failure()`: Returns true when any previous step has failed
- `hashFiles('path/to/files')`: Returns a hash of the specified files

Understanding contexts and expressions is crucial for creating dynamic, responsive workflows that can adapt to different situations. In the next lesson, we'll explore environment files for sharing variables between steps.

<div style="text-align: center">⁂</div>

---

# GitHub Actions: Lesson 20 - Environment Files

Environment files provide a structured way to share data between steps in a GitHub Actions workflow. They're especially useful for passing variables, updating the PATH, and creating workflow summaries.

## Key Environment Files

GitHub Actions uses several special environment files:

1. **`GITHUB_ENV`**: For setting environment variables
2. **`GITHUB_PATH`**: For adding directories to the PATH
3. **`GITHUB_OUTPUT`**: For setting outputs from a step
4. **`GITHUB_STEP_SUMMARY`**: For adding content to the job summary

## Setting Environment Variables

The `GITHUB_ENV` file lets you set environment variables that are available to subsequent steps:

```yaml
steps:
  - name: Set environment variable
    run: |
      echo "RELEASE_VERSION=1.2.3" >> $GITHUB_ENV
      
  - name: Use environment variable
    run: |
      echo "Release version is $RELEASE_VERSION"
```


### Multiline Environment Variables

For multiline values, use a delimiter:

```bash
echo "MULTILINE<<EOF" >> $GITHUB_ENV
echo "Line 1" >> $GITHUB_ENV
echo "Line 2" >> $GITHUB_ENV
echo "Line 3" >> $GITHUB_ENV
echo "EOF" >> $GITHUB_ENV
```


## Setting Step Outputs

The `GITHUB_OUTPUT` file lets you set outputs that can be referenced in later steps:

```yaml
steps:
  - name: Set output
    id: set-version
    run: |
      echo "version=1.2.3" >> $GITHUB_OUTPUT
      
  - name: Use output
    run: |
      echo "Version is ${{ steps.set-version.outputs.version }}"
```


## Modifying PATH

The `GITHUB_PATH` file lets you add directories to the system PATH:

```yaml
steps:
  - name: Add directory to PATH
    run: |
      echo "$HOME/.local/bin" >> $GITHUB_PATH
      
  - name: Use updated PATH
    run: |
      # Commands can now find executables in $HOME/.local/bin
      my-tool --version
```


## Creating Job Summaries

The `GITHUB_STEP_SUMMARY` file lets you create rich summaries that appear in the GitHub UI:

```yaml
steps:
  - name: Create summary
    run: |
      echo "## Test Results" >> $GITHUB_STEP_SUMMARY
      echo "| Test | Result |" >> $GITHUB_STEP_SUMMARY
      echo "|------|--------|" >> $GITHUB_STEP_SUMMARY
      echo "| Test 1 | ✅ Passed |" >> $GITHUB_STEP_SUMMARY
      echo "| Test 2 | ✅ Passed |" >> $GITHUB_STEP_SUMMARY
      echo "| Test 3 | ❌ Failed |" >> $GITHUB_STEP_SUMMARY
```

This creates a Markdown table in the job summary.

## Platform-Specific Syntax

### Windows (PowerShell)

```powershell
# Set environment variable
"RELEASE_VERSION=1.2.3" | Out-File -FilePath $env:GITHUB_ENV -Append

# Set output
"version=1.2.3" | Out-File -FilePath $env:GITHUB_OUTPUT -Append

# Add to PATH
"C:\tools\bin" | Out-File -FilePath $env:GITHUB_PATH -Append

# Create summary
"## Test Results" | Out-File -FilePath $env:GITHUB_STEP_SUMMARY -Append 
```

Environment files provide a robust mechanism for sharing data between steps in your workflows. In the next lesson, we'll explore how to use service containers for testing with databases and other services.

---

# GitHub Actions: Lesson 21 - Service Containers

Service containers allow you to run additional containerized services alongside your workflow jobs. This is especially useful for testing applications that require databases, caching servers, or other services.

## Service Container Basics

Service containers:

- Run in the same network as the job
- Allow you to access services using `localhost` or `127.0.0.1`
- Are isolated per job (not shared between jobs)
- Are automatically removed when the job completes


## Basic Service Container Configuration

```yaml
jobs:
  test:
    runs-on: ubuntu-latest
    
    services:
      postgres:
        image: postgres:13
        env:
          POSTGRES_PASSWORD: postgres
          POSTGRES_USER: postgres
          POSTGRES_DB: test_db
        ports:
          - 5432:5432
        # Optional health check to ensure service is ready
        options: >-
          --health-cmd pg_isready
          --health-interval 10s
          --health-timeout 5s
          --health-retries 5
```


## Accessing Service Containers

Services are available at `localhost` (or `127.0.0.1`) and the mapped port:

```yaml
steps:
  - name: Check PostgreSQL connection
    run: |
      apt-get update
      apt-get install -y postgresql-client
      PGPASSWORD=postgres psql -h localhost -U postgres -d test_db -c "SELECT 1;"
```


## Common Service Container Examples

### MySQL Database

```yaml
services:
  mysql:
    image: mysql:8.0
    env:
      MYSQL_ROOT_PASSWORD: root
      MYSQL_DATABASE: test_db
    ports:
      - 3306:3306
    options: >-
      --health-cmd="mysqladmin ping"
      --health-interval=10s
      --health-timeout=5s
      --health-retries=3
```


### Redis Cache

```yaml
services:
  redis:
    image: redis:6
    ports:
      - 6379:6379
    options: >-
      --health-cmd="redis-cli ping"
      --health-interval=10s
      --health-timeout=5s
      --health-retries=3
```


### MongoDB

```yaml
services:
  mongodb:
    image: mongo:4.4
    env:
      MONGO_INITDB_ROOT_USERNAME: mongo
      MONGO_INITDB_ROOT_PASSWORD: mongo
    ports:
      - 27017:27017
```


## Service Container Networking

GitHub Actions creates a Docker network for each job, allowing services to communicate with each other using service names as hostnames:

```yaml
services:
  app:
    image: my-app:latest
    
  db:
    image: postgres:13
    
steps:
  - name: Test connection between services
    run: |
      # Inside the job container, db service is available as hostname 'db'
      curl http://db:5432
```


## Custom Dockerfile for Services

You can use a custom Dockerfile for services:

```yaml
services:
  custom-service:
    build:
      context: ./docker
      dockerfile: custom.Dockerfile
    ports:
      - 8080:8080
```

Service containers make it easy to test against real service dependencies without mocking, ensuring your tests are more accurate and comprehensive. In the next lesson, we'll explore caching dependencies to speed up your workflows.

---

# GitHub Actions: Lesson 22 - Caching Dependencies

Caching dependencies between workflow runs can significantly improve performance by reusing previously downloaded packages. This reduces build times and network usage, making your workflows faster and more efficient.

## Basic Dependency Caching

GitHub provides the `actions/cache` action to handle dependency caching:

```yaml
steps:
  - uses: actions/checkout@v3
  
  - name: Cache dependencies
    uses: actions/cache@v3
    with:
      path: ~/.npm
      key: ${{ runner.os }}-npm-${{ hashFiles('**/package-lock.json') }}
      restore-keys: |
        ${{ runner.os }}-npm-
  
  - name: Install dependencies
    run: npm ci
```


## Cache Key Strategy

The cache key determines when to reuse or create a new cache:

- **Primary key**: If exact match exists, cache is restored (hit)
- **Restore keys**: If primary key isn't found, restore keys are checked in order
- **Cache miss**: If no matches, a new cache is created with the primary key


## Cache Components

1. **Path**: What to cache (directory or files)
2. **Key**: Unique identifier for the cache
3. **Restore Keys**: Fallback keys if the primary key isn't found

## Language-Specific Caching Examples

### Node.js (npm)

```yaml
- uses: actions/cache@v3
  with:
    path: ~/.npm
    key: ${{ runner.os }}-npm-${{ hashFiles('**/package-lock.json') }}
    restore-keys: ${{ runner.os }}-npm-
```


### Python (pip)

```yaml
- uses: actions/cache@v3
  with:
    path: ~/.cache/pip
    key: ${{ runner.os }}-pip-${{ hashFiles('**/requirements.txt') }}
    restore-keys: ${{ runner.os }}-pip-
```


### Ruby (Bundler)

```yaml
- uses: actions/cache@v3
  with:
    path: vendor/bundle
    key: ${{ runner.os }}-gems-${{ hashFiles('**/Gemfile.lock') }}
    restore-keys: ${{ runner.os }}-gems-
```


### Java (Maven)

```yaml
- uses: actions/cache@v3
  with:
    path: ~/.m2
    key: ${{ runner.os }}-m2-${{ hashFiles('**/pom.xml') }}
    restore-keys: ${{ runner.os }}-m2-
```


## Language-Specific Cache Actions

GitHub provides specialized caching actions for common languages:

```yaml
# Node.js
- uses: actions/setup-node@v3
  with:
    node-version: '16'
    cache: 'npm'

# Python
- uses: actions/setup-python@v4
  with:
    python-version: '3.10'
    cache: 'pip'
```


## Cache Limits and Eviction

- Caches have a 10 GB size limit
- Caches unused for 7 days are automatically removed
- When a repository reaches its storage limit, the oldest caches are evicted

Effective caching can dramatically reduce workflow times by avoiding repeated downloads of dependencies. In the next lesson, we'll explore creating custom JavaScript actions.

---

# GitHub Actions: Lesson 23 - Custom Actions (JavaScript)

JavaScript actions allow you to create custom, reusable functionality for your GitHub Actions workflows. They run directly on the runner without requiring Docker, making them fast and portable.

## JavaScript Action Structure

A basic JavaScript action consists of these files:

1. **`action.yml`**: Metadata file that defines inputs, outputs, and entry point
2. **`index.js`**: Main JavaScript file that contains the action logic
3. **`package.json`**: Node.js package definition with dependencies
4. **`node_modules/`**: Directory containing dependencies

## Creating Your First JavaScript Action

Let's create a simple action that greets a user:

### Step 1: Set Up the Repository Structure

```
my-js-action/
├── action.yml
├── index.js
├── package.json
└── README.md
```


### Step 2: Create the Action Metadata

In `action.yml`:

```yaml
name: 'Hello World'
description: 'Greet someone with a custom message'
inputs:
  who-to-greet:
    description: 'Who to greet'
    required: true
    default: 'World'
  greeting-message:
    description: 'Custom greeting message'
    required: false
    default: 'Hello'
outputs:
  time:
    description: 'The time the greeting was executed'
runs:
  using: 'node16'
  main: 'index.js'
```


### Step 3: Create the JavaScript Code

In `index.js`:

```javascript
const core = require('@actions/core');
const github = require('@actions/github');

try {
  // Get inputs from action.yml
  const nameToGreet = core.getInput('who-to-greet');
  const greetingMessage = core.getInput('greeting-message');
  
  // Log the greeting
  console.log(`${greetingMessage}, ${nameToGreet}!`);
  
  // Get the current time
  const time = new Date().toTimeString();
  
  // Set outputs for other workflow steps
  core.setOutput('time', time);
  
  // Get the JSON webhook payload for the event
  const payload = JSON.stringify(github.context.payload, null, 2);
  console.log(`The event payload: ${payload}`);
} catch (error) {
  core.setFailed(error.message);
}
```


### Step 4: Set Up Dependencies

In `package.json`:

```json
{
  "name": "hello-world-action",
  "version": "1.0.0",
  "description": "A simple hello world GitHub Action",
  "main": "index.js",
  "dependencies": {
    "@actions/core": "^1.10.0",
    "@actions/github": "^5.1.1"
  }
}
```


### Step 5: Install Dependencies

```bash
npm install
```


## Using Your JavaScript Action

Once committed to a repository, use your action in a workflow:

```yaml
jobs:
  hello-job:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      - name: Use my custom action
        uses: username/my-js-action@v1
        with:
          who-to-greet: 'GitHub Actions User'
          greeting-message: 'Hi there'
        id: hello
      - name: Get the output time
        run: echo "The time was ${{ steps.hello.outputs.time }}"
```

JavaScript actions are powerful tools for creating reusable components in your GitHub Actions workflows. In the next lesson, we'll explore Docker-based custom actions for more complex needs.

---

# GitHub Actions: Lesson 24 - Custom Actions (Docker)

Docker-based custom actions allow you to use the full power of container environments for your GitHub Actions. They're ideal for complex actions with specific dependencies or when you need to run in a precisely controlled environment.

## Docker Action Structure

A Docker action consists of these essential files:

1. **`action.yml`**: Metadata file that defines inputs, outputs, and points to the Dockerfile
2. **`Dockerfile`**: Instructions for building the Docker container
3. **`entrypoint.sh`**: Script that runs when the container starts
4. **Other files**: Any additional code or resources needed for your action

## Creating a Docker-Based Action

Let's create a simple Docker action that processes markdown files:

### Step 1: Set Up the Repository Structure

```
markdown-processor/
├── action.yml
├── Dockerfile
├── entrypoint.sh
├── src/
│   └── process.py
└── README.md
```


### Step 2: Create the Action Metadata

In `action.yml`:

```yaml
name: 'Markdown Processor'
description: 'Processes markdown files and generates a report'
inputs:
  markdown-dir:
    description: 'Directory containing markdown files'
    required: true
    default: '.'
  output-file:
    description: 'Output report filename'
    required: false
    default: 'report.json'
outputs:
  file-count:
    description: 'Number of files processed'
runs:
  using: 'docker'
  image: 'Dockerfile'
  args:
    - ${{ inputs.markdown-dir }}
    - ${{ inputs.output-file }}
```


### Step 3: Create the Dockerfile

In `Dockerfile`:

```dockerfile
FROM python:3.9-slim

WORKDIR /app

# Install dependencies
RUN pip install markdown PyYAML

# Copy source files
COPY src/ ./src/
COPY entrypoint.sh /entrypoint.sh

# Make entrypoint executable
RUN chmod +x /entrypoint.sh

# Set entrypoint script
ENTRYPOINT ["/entrypoint.sh"]
```


### Step 4: Create the Entrypoint Script

In `entrypoint.sh`:

```bash
#!/bin/bash
set -e

MARKDOWN_DIR=$1
OUTPUT_FILE=$2

echo "Processing markdown files in $MARKDOWN_DIR..."

# Run the Python script to process markdown files
FILE_COUNT=$(python /app/src/process.py "$MARKDOWN_DIR" "$OUTPUT_FILE")

# Set output for GitHub Actions
echo "file-count=$FILE_COUNT" >> $GITHUB_OUTPUT

echo "Processing complete! Generated $OUTPUT_FILE with $FILE_COUNT files."
```


### Step 5: Create the Processing Script

In `src/process.py`:

```python
#!/usr/bin/env python3
import os
import json
import sys
import markdown
from glob import glob

def process_markdown_files(directory, output_file):
    # Find all markdown files
    md_files = glob(f"{directory}/**/*.md", recursive=True)
    
    results = []
    for file_path in md_files:
        with open(file_path, 'r') as f:
            content = f.read()
            html = markdown.markdown(content)
            word_count = len(content.split())
            results.append({
                'file': file_path,
                'word_count': word_count,
                'html_length': len(html)
            })
    
    # Write results to output file
    with open(output_file, 'w') as f:
        json.dump(results, f, indent=2)
    
    return len(results)

if __name__ == "__main__":
    directory = sys.argv[^25_1]
    output_file = sys.argv[^25_2]
    file_count = process_markdown_files(directory, output_file)
    print(file_count)  # Output for entrypoint.sh to capture
```


## Using Your Docker Action

Once committed to a repository, use your action in a workflow:

```yaml
jobs:
  process-docs:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      
      - name: Process markdown files
        uses: username/markdown-processor@v1
        with:
          markdown-dir: 'docs'
          output-file: 'report.json'
        id: markdown
        
      - name: Show results
        run: echo "Processed ${{ steps.markdown.outputs.file-count }} markdown files"
```


## Docker Action Advantages

1. **Full environment control**: Install any tools or dependencies
2. **Language flexibility**: Use any programming language
3. **System-level operations**: Access to syscalls and low-level operations
4. **Consistency**: Same execution environment every time

Docker-based custom actions provide maximum flexibility for complex automation tasks. In the next lesson, we'll explore composite actions that combine multiple actions and commands.

---

# GitHub Actions: Lesson 25 - Custom Actions (Composite)

Composite actions allow you to combine multiple steps into a single, reusable action without requiring JavaScript or Docker containers. They're perfect for bundling sequences of steps that you use frequently across workflows.

## Composite Action Structure

A composite action requires just one main file:

1. **`action.yml`**: Metadata file that defines inputs, outputs, and a sequence of steps

## Creating a Composite Action

Let's create a composite action that sets up a common development environment:

### Step 1: Create the Action Metadata File

Create an `action.yml` file:

```yaml
name: 'Setup Development Environment'
description: 'Sets up Node.js, Python, and common tools'

inputs:
  node-version:
    description: 'Node.js version'
    required: false
    default: '16'
  python-version:
    description: 'Python version'
    required: false
    default: '3.9'
  install-dependencies:
    description: 'Whether to install dependencies automatically'
    required: false
    default: 'true'

outputs:
  cache-hit:
    description: 'Whether dependencies were restored from cache'
    value: ${{ steps.node-cache.outputs.cache-hit }}

runs:
  using: "composite"
  steps:
    - name: Setup Node.js
      uses: actions/setup-node@v3
      with:
        node-version: ${{ inputs.node-version }}
        cache: 'npm'
      id: node-cache
    
    - name: Setup Python
      uses: actions/setup-python@v4
      with:
        python-version: ${{ inputs.python-version }}
        cache-dependency-path: '**/requirements.txt'
    
    - name: Install global tools
      run: npm install -g jest prettier eslint
      shell: bash
    
    - name: Install Node.js dependencies
      if: inputs.install-dependencies == 'true'
      run: npm ci
      shell: bash
    
    - name: Install Python dependencies
      if: inputs.install-dependencies == 'true' && hashFiles('**/requirements.txt') != ''
      run: pip install -r requirements.txt
      shell: bash
```


## Key Components of a Composite Action

1. **Metadata**: Name and description of the action
2. **Inputs**: Parameters that can be passed to the action
3. **Outputs**: Values that the action passes back to the workflow
4. **Runs**: Specifies that this is a composite action and lists the steps
5. **Steps**: A sequence of actions and shell commands to execute

## Important Requirements

Each step in a composite action must include either:

- `uses` to reference another action
- `run` with a corresponding `shell` property


## Using Your Composite Action

Once committed to a repository, use your composite action in a workflow:

```yaml
jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      
      - name: Set up development environment
        uses: username/setup-dev-environment@v1
        with:
          node-version: '18'
          python-version: '3.10'
          install-dependencies: 'true'
        id: setup
      
      - name: Show cache status
        run: echo "Cache hit: ${{ steps.setup.outputs.cache-hit }}"
```


## Benefits of Composite Actions

1. **Simplicity**: Easier to create than JavaScript or Docker actions
2. **Reusability**: Bundle common sequences of steps
3. **Maintainability**: Update in one place, changes appear everywhere
4. **No build step**: Unlike JavaScript actions, no need to commit node_modules

Composite actions are an excellent way to standardize common workflows across your repositories. In the next lesson, we'll explore how to set up CI workflows for Node.js applications.

---
