# nrwsoft-workspaces

## Get Started
1. Create $HOME/workspaces or any other directory of your liking and enter it - the path will be available as $workspaces\_home
2. Clone this repository into src/ (this is important, you can not rename src/) - the path will be available as $workspaces\_src\_path
3. Create or locate your workspace home - the path will be available as $ws\_home
3. Copy init-workspace.template into $wsHome and rename to init-workspace
4. Modify init-workspace to your liking and add all the needed environment variables - they’ll automatically be set globally and are then available in your workspace session
5. If needed create a $ws\_home/bin directory and add all supporting binaries or scripts into this folder, they’ll be available in your workspace session
6. Enter $workspaces\_home and symlink $ws\_home/init-workspace to project-name - the name of the symlink will be available as $ws\_name and shown as the session name
7. Execute ./project-name and you successfully entered the workspace session
