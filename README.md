# Gemini CLI Extension - Spanner

This Gemini CLI extension provides a set of tools to interact with [Google Cloud Spanner](https://cloud.google.com/spanner/docs) instances. It allows you to manage your databases, execute queries, and explore schemas directly from the [Gemini CLI](https://google-gemini.github.io/gemini-cli/), using natural language prompts.

Learn more about [Gemini CLI Extensions](https://github.com/google-gemini/gemini-cli/blob/main/docs/extension.md).

## Features

* **Natural Language Management:** Stop wrestling with complex commands. Explore schemas and query data by describing what you want in plain English.
* **Seamless Workflow:** As a Google-developed extension, it integrates seamlessly into the Gemini CLI environment. No need to constantly switch contexts for common database tasks.
* **Code Generation:** Accelerate development by asking Gemini to generate data classes and other code snippets based on your table schemas.

## Prerequisites

Before you begin, ensure you have the following:

*   [Gemini CLI](https://github.com/google-gemini/gemini-cli) installed.
*   A Google Cloud project with the **Spanner API** enabled.
*   IAM Permissions
    * Cloud Spanner Database Reader (`roles/spanner.databaseReader`)
    * Cloud Spanner Database User (`roles/spanner.databaseUser`)

## Installation

To install the extension, use the command:

```bash
gemini extensions install github.com/gemini-cli-extensions/spanner
```

## Configuration

Set the following environment variables before starting the Gemini CLI:

*   `SPANNER_PROJECT`: The GCP project ID.
*   `SPANNER_INSTANCE`: The Spanner instance ID.
*   `SPANNER_DATABASE`: The Spanner database ID.
*   `SPANNER_DIALECT`: (Optional) The Spanner database dialect e.g. "googlesql" or "postgresql" (Default: "googlesql")

## Usage

*   **Explore Schemas and Data:**
    * "Show me all tables in the 'orders' database."
    * "What are the columns in the 'products' table?"
    * "How many orders were placed in the last 30 days, and what were the top 5 most purchased items?"

*   **Generate Code:**
    * "Generate a Python dataclass to represent the 'customers' tab

## Supported Tools

* `list_tables`: Use this tool to list tables and descriptions.
* `execute_sql`: Use this tool to execute any SQL statement.
* `execute_sql_dql`: Use this tool to execute DQL SQL statement.

## Additional Extensions

Find additional extensions to support your entire software development lifecycle at [github.com/gemini-cli-extensions](https://github.com/gemini-cli-extensions).

## Troubleshooting

* "cannot execute binary file": Ensure the correct binary for your OS/Architecture has been downloaded. See [Installing the server](https://googleapis.github.io/genai-toolbox/getting-started/introduction/#installing-the-server) for more information.
