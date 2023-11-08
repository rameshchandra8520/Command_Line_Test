## Introduction

Command-Line Test: A Bash Shell Tool Simulating Online Testing with User Authentication and Answer Storage.

This tool provides a command-line interface for users to log in, take tests, and store their answers for future verification. It is designed to simulate an online testing scenario using Bash shell scripting and commands, incorporating shell programming constructs, pattern matching commands (e.g., grep, sed), and file-handling features such as permissions and directories. It serves as a lightweight alternative to full-fledged online testing platforms, making it a convenient choice for text-based testing.

## Getting Started
```
Sign In
a. Take Test
b. View Test
Sign up 
Exit
```
- Using sign-up new user can register with a User-ID and Password.
- Already Registered User can Sign-in with ID and Password.
- All activities are logged in a "Test_Log.txt" file, including date and time.
- Questions are presented one by one with multiple-choice options. You can edit them in the "questions.txt" file.
- Every question is timed, with the default being 15 seconds. You can modify the time in the script as needed.
