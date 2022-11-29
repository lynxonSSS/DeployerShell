# DeployerShell
The deployer shell file is an executable file that can be used by anyone to execute or deploy any project. Thus making the tedious process of pulling from git / Killing the port / going to the path are skipped for smooth deployment.

# Help
This tool helps in single command deloyment for any kind of technology.
The tool gets the project directory and based on user input identifies availability
of git and then hard resets to latest head and then pulls the code.
Then it takes the command input by the user to deploy the project. 
Port is used only to kill the currently running project and it doesn't mean
that the project will be started on any port entered.

Options:

--help / -H        Print this Help.\n
\n
-V / --version     Prints the version.\n
-d                 Specify the project root directory.\n
-p                 Specify the port to be killed.\n
-c                 Specify the command to be executed on the root directory specified.\n
-g                 Specify if git is configured or if pull is required.\n
