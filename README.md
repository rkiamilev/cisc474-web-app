# cisc474-project-starter

A repo that you can fork to make new projects

# Setup

-   Clone this repo
-   NVM and the right version of Node
    -   Install Node.
    -   Make sure you have at least version 22.12.\*, not lower. Run `node -v` to check your version.
    -   Windows: You can have multiple versions of Node using NVM: <https://github.com/coreybutler/nvm-windows>
    -   Mac: You can get NVM to manage multiple versions: https://github.com/nvm-sh/nvm?tab=readme-ov-file#install--update-script
    -   Either way, use `nvm list` and `nvm use` to switch between Node versions, and make sure you get onto a version 22.12.\* or higher.
-   Install dependencies
    -   `cd` into your cloned project directory
    -   Run `npm install` to install the project dependencies
-   Docker:
    -   Install Docker Desktop from <https://www.docker.com/products/docker-desktop>

# Deployment

-   Database:
    -   SupaBase Free Tier: https://supabase.com/
    -   Directions:
        -   Start a new project on the Free Tier
        -   Login using your Github
        -   Create a new organization:
            -   Name: Your choice, e.g., `CISC474 F25 Projects` (you can change this later)
            -   Type: `Educational`
            -   Price: `Free - $0/month`
        -   Create a new project:
            -   Organization: Choose your previously selected organization
            -   Project name: Name according to assignment, e.g., `acbart lms`
            -   Database Password: Click the "Generate Password" text, then make sure you securely record the password (e.g., with your browser's automatic password saving features)
            -   Region: `East US (North Virginia)`
        -   You can now get your connection details for this database
