# Lab Setup

Complete the following tasks to prepare your development environment prior to completing the labs.

## Lab prerequisites

You need the following tools to complete the labs for this course:

- Admin access to a Microsoft 365 tenant.
- An Azure subscription.
- Visual Studio Code.
- Teams Toolkit Visual Studio Code Extension:  Version 5.2.0 or higher. (You will install this during the lab)
- The Microsoft Teams client (for work or school), or access to Microsoft Teams via a web browser.
- Node.js version 16.14.2.

## Install nvm-windows

You'll use this tool to install Node.js and optionally switch Node versions as needed for your projects.

1. In a web browser, navigate to [https://github.com/coreybutler/nvm-windows/releases](https://github.com/coreybutler/nvm-windows/releases).
2. Locate the latest release version and select the **nvm-setup.zip** file to download.  The file will be downloaded to your machine. ![Screenshot of nvm-setup.zip download](../../media/download-nvm-setup.png)
3. Open the file folder and **extract** the contents of the zip folder to a folder on your machine.
4. From the new folder, select **nvm-setup.exe** to open the setup file.
5. Follow the prompts in the installer to install the tool using the default options. ![Screenshot of setup nvm install](../../media/install-nvm.png)
6. Nvm for Windows will be installed on your machine.

## Install Node.js

Install Node.js version 16.14.2, which is compatible with all of the solutions in this course.

1. Open the **Command Prompt** application.
2. Enter the command `nvm install 16.14.2` to install Node.js.
3. The nvm output should confirm that installation is complete.
4. Run the command `nvm use 16.14.2` to use this version of Node.js.
5. Run the command `node -v` to confirm that you have version 16.14.2 installed.

You have now installed and configured Node.js version 16.14.2 ![Screenshot of install npm](../../media/nvm-install-npm.png)

## Azure subscription

Note that if you have been provided with Azure login information, a resource group has already been created for your use.  For Provisioning tasks throughout the labs, when prompted to "select a resource group or create a new resource group," **select the provided resource group**.

## Debugging Teams apps

When debugging your Teams app locally, you may be prompted to install a development certificate for localhost.  You will need to do this in order to debug locally.

When prompted, select **Install**.

![Screenshot of the prompt to install dev certificate.](../../media/install-certificate.png)

Then select **Yes** in the Security Warning dialog.

![Screenshot of the security dialog.](../../media/development-certificate.png)

Visit the Teams documentation to learn more: [Debug your Teams app locally](https://learn.microsoft.com/microsoftteams/platform/toolkit/debug-local?tabs=Windows&pivots=visual-studio-code-v5)
