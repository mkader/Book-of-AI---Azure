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


* Linux (install)
* Dev Container (VS Code)
* Codespaces (GitHub)
