# nrwsoft-workspaces

## Get Started
1. Create $HOME/workspaces or any other directory of your liking and enter it - the path will be available as $workspacesHome
2. Clone this repository into src/ (this is important, you can not rename src/) - the path will be available as $workspacesSrcPath
3. Create or locate your workspace home - the path will be available as $wsHome
3. Copy init-workspace.template into $wsHome and rename to init-workspace
4. Modify init-workspace to your liking and add all the needed environment variables - they’ll automatically be set globally and are then available in your workspace session
5. If needed create a $wsHome/bin directory and add all supporting binaries or scripts into this folder, they’ll be available in your workspace session
6. Enter $workspacesHome and symlink $wsHome/init-workspace to project-name - the name of the symlink will be available as $wsName and shown as the session name
7. Execute ./project-name and you successfully entered the workspace session
