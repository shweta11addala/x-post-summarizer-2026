# X Post Summarizer 2026

This repository provides an AI-generated summary of a public figure's 2026 X posts, specifically analyzing the account handle @llm_wizard. The project is built using a LangGraph agent combined with GitHub MCP tools for repository operations and the X API v2 for retrieving posts.

## Project Description

The goal of this project is to summarize recent posts from a public figure on X (formerly Twitter) using AI techniques. It leverages the X API to fetch recent posts and uses automated tools to analyze and generate summaries.

## How It Was Built

- Utilizes a LangGraph agent to orchestrate the workflow.
- Employs GitHub MCP tools to manage repository files and branches.
- Uses the X API v2 to search and retrieve recent posts from the specified user.

## Replicating the Process

To replicate this project, follow these steps:

1. Obtain an X API Bearer Token by creating a developer account on the X platform and generating the necessary credentials.
2. Set the Bearer Token as an environment variable in your system:

   ```bash
   export X_BEARER_TOKEN='your_bearer_token_here'
   ```

3. Install the required Python dependencies:

   ```bash
   pip install requests
   ```

4. Use the provided `x_search.py` script to fetch recent posts from any public X account by running:

   ```bash
   python x_search.py <account_handle>
   ```

   Replace `<account_handle>` with the desired X username.

This setup allows you to fetch and analyze recent posts, enabling you to generate summaries similar to those in this repository.
