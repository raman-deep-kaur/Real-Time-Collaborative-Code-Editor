# Code-Editor

A **real-time, web-based** collaborative code editor that allows multiple users to code together in the same environment. The platform enables developers to **write, edit, and execute** code collaboratively with seamless communication.

## Features
- **Real-time Collaboration** - Multiple users can edit the same file simultaneously.
- **Multi-User Rooms** - Users can create or join unique rooms for coding sessions.
- **WebSocket Integration** - Ensures instant updates using **Flask-SocketIO**.
- **Code Execution Support** - Runs code in different programming languages.
- **Syntax Highlighting** - Improves readability with **CodeMirror Editor**.
- **File Management** - Allows users to create, delete and rename files.



##  Getting Started
###  Setup
1. Clone the repository:

2. Create a Docker image:
   ```bash
   docker build -t collabrix .
   ```

3. Run a container from the `collabrix` image:
   ```bash
   docker run -p 5000:5000 collabrix
   ```

4. Open the app in your browser:
   ```
   http://localhost:5000
   # or replace "privateip" with your private IP address (e.g., 10.12.233.104)
   http://privateip:5000
   ```


