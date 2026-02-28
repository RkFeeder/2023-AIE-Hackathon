# 2023 AIE Hackathon – GPA & Graduation Manager

**1st Place** — 2023 Applied Information Engineering Hackathon

## Overview
A web-based academic management tool built in 24 hours by a team of three. The app helps students track their GPA and monitor graduation requirements through an intuitive browser interface — built with Streamlit instead of the terminal output used by most competing teams.

## Features
- **GPA Calculator** — Input courses and grades to compute current GPA
- **Graduation Requirement Checker** — Track completed and remaining credits by category
- **Excel Import/Export** — Upload and download `.xlsx` files containing course and grade data

## Tech Stack
| Tool | Purpose |
|---|---|
| Python | Core logic |
| Streamlit | Web UI |
| Pandas | Excel file handling |

## How to Run
```bash
# Install dependencies
pip install -r requirements.txt

# Launch the app
streamlit run main.py
