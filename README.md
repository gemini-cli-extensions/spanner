# Gemini CLI Extension - Spanner

This Gemini CLI extension provides a set of tools to interact with [Google Cloud Spanner](https://cloud.google.com/spanner/docs) instances. It allows you to manage your databases, execute queries, and explore schemas directly from the [Gemini CLI](https://google-gemini.github.io/gemini-cli/), using natural language prompts.

## Features

*   **Integrated with Gemini CLI:** As a Google-developed extension, it integrates seamlessly into the Gemini CLI environment, making security an accessible part of your workflow.
*   **Connect to Spanner:** Securely connect to your Spanner instances.
*   **Explore Database Schema:** List instances, databases, and tables.
*   **Query your Database:** Execute SQL queries against your database.

## Supported Tools

* list-tables: Use this tool to list tables and descriptions.
* execute-sql: Use this tool to execute any SQL statement.
* execute-sql-dql: Use this tool to execute DQL SQL statement.

## Prerequisites

Before you begin, ensure you have the following:

*   [Gemini CLI](https://github.com/google-gemini/gemini-cli) installed.
*   A Google Cloud project with the **Spanner API** enabled.
*   IAM Permissions

## Installation

To install the extension, use the `gemini extensions install` command:

```bash
gemini extensions install github.com/gemini-cli-extensions/spanner.git
```

## Configuration

*   `SPANNER_PROJECT`: The GCP project ID.
*   `SPANNER_INSTANCE`: The Spanner instance ID.
*   `SPANNER_DATABASE`: The Spanner database ID.


## Usage

* Provision Infrastructure
* Explore Schemas and Data
* Generate code


## Security

This extension executes commands against your Spanner database. Always review the generated SQL queries before execution, especially for write operations.

## Disclaimer

This is not an officially supported Google product. This extension is under active development, and breaking changes may be introduced.
