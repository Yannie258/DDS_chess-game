# Setup
cd <yourProjectLocation>
npm install
nodemon start
Open your browser and visit http://localhost:3000/
## Some errors can happen
### 1. Error: nodemon : File nodemon.ps1 cannot be loaded because running scripts is disabled on this  system. For more information, see about_Execution_Policies at https:/go.microsoft.com/fwlink/?LinkID=135170.
### Solved:
--> open Powershell (not cmd) run as administrator:
--> Set-ExecutionPolicy RemoteSigned -Scope CurrentUser 
--> Yes for changing the policy and enter
## 2. Warning: in the working copy of 'node_modules/npm/test/tap/umask-lifecycle.js', LF will be replaced by CRLF the next time Git touches it
### Solved:
git config --global core.autocrlf false


