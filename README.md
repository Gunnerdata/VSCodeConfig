# VSCode/GIT Step

* Application - Git
  * https://git-scm.com/
  
* Application - VS Code
  * https://code.visualstudio.com/
  
* VS Code Exstension
    * Git (submodule) Assistant
        * ivanhofer.git-assistant
    * PowrShell
        * ms-vscode.powershell
    * psioniq File Header
        * psioniq.psi-header
    * Todo Tree
        * gruntfuggly.todo-tree

* PS Modules
  * Pester

* VS Code Config
    * settings.json

# Command fo above stuff

## Install script from Powershell Gallery

Install-Script -Name Install-VSCode

Install-Script -Name install-gitscm

## Install applications and exstentions

install-gitscm

Install-VSCode -AdditionalExtensions @("ivanhofer.git-assistant","ms-vscode.powershell","psioniq.psi-header","gruntfuggly.todo-tree")

## Install PS Modules

Install-Module -Name Pester -Force -SkipPublisherCheck

## Copy settings.json to local computer



  
