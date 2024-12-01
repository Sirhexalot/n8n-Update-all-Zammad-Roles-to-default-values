# n8n Workflow: Update All Zammad Roles to Default Values

This repository contains an n8n workflow designed to reset all user roles in a Zammad instance to specified default values. This ensures consistent role management and simplifies administrative tasks.

## Features
- Fetches all active users from Zammad.
- Updates user roles to a predefined set of default roles.
- Excludes specific users from the update process based on their IDs.
- Easily configurable for different Zammad environments.

## Setup
1. **Import the Workflow**:
   - Download the `.json` workflow file.
   - Import it into your n8n instance.
2. **Configure Variables**:
   - **`zammad_base_url`**: Set your Zammad instance's base URL.
   - **`zammad_api_key`**: Provide your Zammad API key.
   - **`default_roles`**: Define the default role IDs to assign.
   - **`exclude_zammad_users_by_id`**: List the user IDs to exclude from the update.
3. **Run the Workflow**:
   - Trigger the workflow to automatically reset roles for all active users (excluding specified IDs).

## Contribution
We welcome feedback and contributions! If you encounter bugs or have ideas for improvements, please submit an issue or pull request.

---

**Note**: Ensure that the API key has the necessary permissions to manage roles in your Zammad instance.
