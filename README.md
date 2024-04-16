# Bep
### A Simple Version Control System
#### it is a simple version control system built using Node.js[JavaScript]


## Installation
To get started, make sure you have latest version of Node.js installed. Then, follow these steps:

1. Clone this repository.
```bash
git clone https://github.com/bishalde/bep.git
```

2. Navigate to the project directory in your terminal.
```bash
cd bep
```

3. Install the required dependencies by running.
```bash
npm install
```

4. 
```bash
npm link
```

## Commands and Use Cases

1. Initialize a Repository

Initialize an empty Bep repository in your project directory.
```bash
bep init
```
![Iniatialize Repository](/ScreenShots/init.png)

2. Configuration

View or set configuration options for your Bep repository.
```bash
bep config <key> [value]
```
![Iniatialize Repository](/ScreenShots/config.png)

3. Add Changes to Staging

Add changes in the working directory to the staging area. You can specify multiple file paths to add.
```bash
bep add <paths...>
```
![Iniatialize Repository](/ScreenShots/add.png)

4. Commit Changes
Capture a snapshot of the project's currently staged changes with a commit message.
```bash
bep commit <message>
```
![Iniatialize Repository](/ScreenShots/commit.png)

5. Display Repository Status
Display the state of the working directory and the staging area
```bash
 bep status
```
![Iniatialize Repository](/ScreenShots/status.png)

6. Pretty-print Commit Logs
Display the contents of the commit logs.
```bash
bep log
```
![Iniatialize Repository](/ScreenShots/log.png)

7. Revert a File to a Previous Version
Revert a file to the last committed version or a specific commit using the -c option.
```bash
bep checkout <filepaths...>
```
```bash
bep checkout -c <commitId> <filepaths...>
```