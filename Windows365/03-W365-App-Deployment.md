# Challenge 3: Deploy application via Intune

[Previous Challenge](./02-W365-RDP-Properties.md) - **[Home](../../README.md)** - [Next Challenge](./04-W365-Flex-Provisioning.md)

## Introduction

As an IT-admin, one of the easiest ways to get started with Windows 365 is to create Cloud PCs with default gallery images of Windows 10/11 Enterprise. 

After provisioning, you can customize the user experience by using Intune to push apps to your users’ Cloud PCs. These images can include existing Windows client apps already in your Intune environment. Since these Cloud PC devices are enrolled in Intune, you can treat them like any other Windows device in your environment.

## Challenge

It is important that your users have following applications installed* :
- **Visual Studio Code**
- **GIMP** (automatic update enabled)
- **VideoLAN VLC media player**

> [!NOTE]
> You can choose to deploy the app either as a *Win32 application*  or as a *Microsoft Store app* or a *Windows catalog app*

If you decide to deploy Visual Studio Code as a Win32 application, use a unique app name format such as: **App-P[count]-YourAppName**. 

## Success Criteria

- Application Visual Studio Code is assigned and installed on your Cloud PC.

## Learning Resources
- [Windows 365 and Apps](https://learn.microsoft.com/en-us/windows-365/enterprise/app-overview)
- [How to create an Intune App](https://learn.microsoft.com/en-us/mem/intune/apps/apps-win32-prepare)
- [How to assign apps to groups](https://learn.microsoft.com/en-us/mem/intune/apps/apps-deploy)
