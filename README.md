# Jira Reporting Made Easy

<p style="text-align: center;"><em>Powered by Google ADK &amp; Atlassian MCP</em></p>

**This agent analyzes JIRA ticket cycle times and state workflow transitions through interactive visualizations.** It processes individual ticket changelogs to extract state transitions with timestamps, then generates Sankey diagrams, histograms, and bar charts to reveal workflow patterns and bottlenecks. 

The agent works with any JIRA instance and is perfect for product managers, engineering leads, and process improvement teams who need data-driven insights into their development workflows.

[![Watch on YouTube](https://img.shields.io/badge/Watch%20on-YouTube-red?logo=youtube&style=for-the-badge)](https://youtu.be/vKniUPrz51Y) 


**Key Features**

* Sankey Flow Diagrams - Visual workflow paths showing ticket movement between states
* State Time Histograms - Distribution analysis for cycle time spent in specific states
* Comparative Bar Charts - Total time analysis across all workflow states

If you have any questions or would like to collaborate, feel free to reach out to me on [LinkedIn](https://www.linkedin.com/in/jenya-stoeva-60477249/). You're more than welcome!

## How-To 

**Prerequisites** to run the **JIRA Ticket Cycle Time & State Workflow Analytics agent** with an MCP connection, you need:

* Python 3.13
* JupyterLab (installed inside the venv) to run this notebook.
* Node.js - includes npx, which is used to launch the MCP client (mcp-remote) on the fly without a global install.
* Access to the Atlassian MCP endpoint: https://mcp.atlassian.com/v1/sse and permissions to read JIRA ticket data.
* JIRA instance credentials (email, API token, and base URL) configured as environment variables.
