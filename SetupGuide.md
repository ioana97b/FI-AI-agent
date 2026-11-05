Useful links: https://help.sap.com/docs/joule-studio/joule-studio/joule-studio-for-cli-pro-code-development-in-joule-studio 

Use this link to have a step by step guide for activating and developing with Joule Studio CLI. 

 

Important notes: 

Node.js version 24 or later installed ( see here -> https://nodejs.org/en/download ) 

An account on Joule Studio ( see here -> https://workzone.one.int.sap/site#workzone-home&/groups/cRnIIs7rsF7ODpy1ZyoDmS/workpage_tabs/lnK2lRegIPWPU5Q7z0M1WB ) 

An AI coding agent installed locally ( Claude Code or OpenCode ). Note -> you must have Hyperspace AI installed for proxy server -> this is for being able to use Claude 

You must add node.js to PATH 

 

After you installed node ( and npm automatically ), do these steps to install Joule for CLI using your terminal: 

npm install -g @sap/joule-studio-cli 

Note: If you installed it previously, use the command below to uninstall it and install it again after. 

npm uninstall -g @sap/joule-work-dev-cli-early-adopters@prerelease 

Verify the installation using the command: jl v 

 

IMPORTANT 

After you install Joule, you must login to a landscape. 

 

To do so, you must do the following steps: 

Open Joule Studio in your browser. 

Select your user icon in the bottom-left corner and choose Settings. 

Go to Develop. 

Under CLI Authentication setup, copy the Sign-in URL. 

 

Then run the following command: 
jl login "<your Sign-in URL>" 

 

*TO LOGOUT AND CLEAN THE SESSION: jl logout 

 

Useful Links: 

Pro-Code Setup -> https://help.sap.com/docs/joule-studio/joule-studio/pro-code-setup 

Create an agent with the CLI -> https://help.sap.com/docs/joule-studio/joule-studio/create-agent-with-cli 

AI coding agent -> https://help.sap.com/docs/joule-studio/joule-studio/ai-coding-agent 

Pro-Code Workflow -> https://help.sap.com/docs/joule-studio/joule-studio/pro-code-workflow 

Solution Structure ( important ) -> https://help.sap.com/docs/joule-studio/joule-studio/solution-structure 

CLI Reference ( every command of the Joule CLI ) -> https://help.sap.com/docs/joule-studio/joule-studio/cli-reference 