# sql-bug-testing-demo

A lightweight SQL project demonstrating how QA-Style bug tracking can be analyzed using 
relational databases. This project simulates game testing environment with testers, test sessions, and discovered bugs.

## What this project demonstrates
- Creating relational tables for QA Workflows
- Inserting structured test data
- Analyzing bugs by category, severity, tester, and build version
- Using JOINs to combine QA data
- Using window functions to rank severity impact
- Identifying recurring issues and patterns

## Tables
- **bugs** - individual bug reports
- **testers** - QA testers and experience levels
- **sessions** - test sessions and build versions

## Example Insights
- Which tester finds the most bugs
- Which build version has the most issues
- Severity distribution across the project
- Recurring categories (UI, Audio, AI)
- Ranking severity impact per tester

  This project is designed to showcase SQL skills for QA and data analyst roles.
