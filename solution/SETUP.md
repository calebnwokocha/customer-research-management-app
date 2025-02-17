# Customer Research Management App Setup

Follow these instructions to deploy and configure the Customer Research Management App using Power Apps.

## Prerequisites
- An active Microsoft Power Platform environment with administrative privileges.
- The required dependencies (e.g., `AppModuleWebResources` and `PowerAppsAppFramework`) should be available in the environment.
- Import will fail if these managed solutions do not exist in the target environment: **App Framework Infra Extensions:** `msdyn_AppFrameworkInfraExtensions` version `1.0.0.12` and **App Module Assets:** `AppModuleWebResources` version `2.5`

## Setup Steps

### 1. Download the Solution Package
Download the solution file from this [repository](https://github.com/calebnwokocha/customer-research-management-app/tree/main/solution).

### 2. Log in to Power Apps
- Go to the [Power Apps Maker Portal](https://make.powerapps.com/) in your browser.
- Sign in with your Microsoft credentials.

### 3. Import the Solution
- In the Power Apps Maker Portal, select **Solutions** from the left sidebar.
- Click on **Import solution**.
- Browse and select the downloaded solution file.
- Follow the on-screen prompts to complete the import process.

### 4. Publish Customizations
After the solution is successfully imported, click **Publish** to apply the customizations.
