# DAILY REPORT ASSISTANT
[English](README.md) | [中文](README_CN.md)

## 🌟 Introduction

The **Daily Report Assistant** is a powerful skill designed to streamline your daily reporting workflow. It automates the creation, management, and organization of your daily work logs in Markdown format.

Whether you are a developer tracking commits 👨‍💻, a project manager updating status 👩‍💼, or anyone who needs to keep a record of their daily achievements, this skill is your perfect companion! 🚀

## 🎯 Scenarios

- **Automated Report Generation**: Create a new daily report file with a single command.
- **Effortless Updates**: Add completed tasks, issues, and plans for tomorrow on the fly.
- **Smart Management**: Modify or delete specific entries using simple natural language commands.
- **Structured Logging**: Keep your reports consistent with automatically numbered lists and categorized sections.

## 🛠️ Configuration & Installation

Assuming you are using **Kimi** (or a compatible AI assistant), follow these steps to install the skill:

1.  **Locate Skills Directory**: Navigate to your skills folder, typically located at `~/.kimi/skills`.
2.  **Clone/Copy**: Place the `daily-report-assistant` folder into the skills directory.
    ```bash
    cp -r daily-report-assistant ~/.kimi/skills/
    ```
3.  **Verify Structure**: Ensure the folder contains `SKILL.md` which defines the skill's capabilities.

### ⚙️ Customization

You can customize the default storage path and file format by editing the `SKILL.md` file or by specifying preferences in your prompts.

- **Default Path**: `G:\file\工作汇报\周报` (Windows example)
- **File Format**: `日报_YYYY_MM_DD.md`

## 📖 Usage Guide

Once installed, simply chat with your assistant to manage your reports! 🗣️

### 1. Create a Report
> "Build today's daily report"
> "Create a report for 2023-10-27"

This will generate a file like `日报_2023_10_27.md` with standard sections:
- `## Completed Today`
- `## Issues and Risks`
- `## Plan for Tomorrow`

### 2. Add Items
> "Add: Finished the login page refactoring"
> "Record: Fixed the payment callback bug in Issues"

The assistant will append the item with a unique ID:
`- [#1] Finished the login page refactoring`

### 3. Modify Items
> "Change #1 to: Finished login page refactoring and added unit tests"

### 4. Delete Items
> "Delete #2"
> "Remove the item about the payment bug"

---

Happy Reporting! 📝✨
