## Azure ai CLI Installation
* The Azure AI CLI is a cross-platform CL tool to connect and immediately use Azure AI services with or without writing code.

### Windows (install)
  * <a href="https://learn.microsoft.com/en-us/windows/package-manager/winget/#install-winget">Install WinGet</a>
  1. Use winget to install the .NET 8 SDK - "winget install -e --id Microsoft.DotNet.SDK.8"
  1. Use winget to install the Azure CLI (az) - "winget install -e --id Microsoft.AzureCLI"
  1. Use dotnet to install the Azure AI CLI (ai) - "dotnet tool install -g Azure.AI.CLI --prerelease"

### Mac (install)
  * <a href ="https://brew.sh/">Install Homebrew</a> 
  1. Use brew to install the .NET 8 SDK - "brew install --cask dotnet-sdk"
  1. Use brew to install the Azure CLI (az) - "brew install azure-cli"
  1. Use dotnet to install the Azure AI CLI (ai) - "dotnet tool install -g Azure.AI.CLI --prerelease"

### Linux (install)
 * <a href="https://curl.se/download.html">Install curl</a>
 1. Use curl to download the script & Use bash to run the script - "curl -sL https://aka.ms/InstallAzureAICLIDeb | sudo bash"

### Dev Container (VS Code)
1. Use git to clone the repository - "git clone https://github.com/Azure/azure-ai-cli"
1. Use code to open the folder - "code azure-ai-cli"
1. Then, click the "Reopen in Container" button in the notification.
   1. If the "Reopen in Container" notification does not appear ...
   1. Open the command palette and run the Dev Containers: Reopen in Container command.

### Codespaces (GitHub)
 1. You can run the Azure ai CLI in a browser using GitHub Codespaces - <a href="https://codespaces.new/Azure/azure-ai-cli?quickstart=1">Open in GitHub Codespaces</a>
