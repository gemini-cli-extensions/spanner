# Spanner Extension

This document provides instructions for the Gemini agent to assist users with the Spanner extension.

## Spanner MCP Server (Data Plane: Connecting and Querying)

This section covers connecting to a Spanner instance.

1.  **Verify Environment Variables**: Before attempting to connect, confirm with the user that the following environment variables are set in the extension configuration or their shell environment.

    *   `SPANNER_PROJECT`: The GCP project ID.
    *   `SPANNER_INSTANCE`: The Spanner instance ID.
    *   `SPANNER_DATABASE`: The Spanner database ID.

2.  **Handle Missing Variables**: If a command fails with an error message containing a placeholder like `${SPANNER_PROJECT}`, it signifies a missing environment variable. Inform the user which variable is missing and instruct them to set it.

3.  **Handle Permission Errors**: If you encounter permission errors, ensure the user has the correct Spanner permissions (e.g., `spanner.databases.get`, `spanner.databases.select`).
