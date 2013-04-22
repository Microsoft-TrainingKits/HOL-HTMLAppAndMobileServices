<a name="HOLTitle"></a>
# Getting Started with Windows Azure Mobile Services and HTML Applications #

---
<a name="Overview"></a>
## Overview ##

Windows Azure Mobile Services is a Windows Azure service offering designed to make it easy to create highly-functional mobile apps using Windows Azure. Mobile Services brings together a set of Windows Azure services that enable backend capabilities for your apps. These capabilities includes simple provisioning and management of tables for storing app data, integration with notification services, integration with well-known identity providers for authentication, among others.

This hands-on lab shows you how to add a cloud-based backend service to an HTML app using Windows Azure Mobile Services. You will create both a new mobile service and a simple To do list app that stores app data in the new mobile service. You can view a video version of this tutorial by clicking the clip to the right.

A screenshot from the completed app is below:

![completed-app](images/completed-app.png?raw=true "Completed HTML Application")

<a name="Objectives"></a>
### Objectives ###

In this hands-on lab, you will learn how to:

- ...

<a name="Prerequisites"></a>
### Prerequisites ###

The following is required to complete this hands-on lab:

- One of the following Web Servers running on your computer:
	- On Windows: [IIS Express](1).
	- On MacOS X: Python, which should already be installed.
	- On Linux: Python. You must install the latest version of Python.
- A web browser that supports HTML5.
- A Windows Azure subscription account that has the Windows Azure Mobile Services feature enabled

	>**Note:** If you don't have an account, you can create a free trial account in just a couple of minutes. For details, see [Windows Azure Free Trial](http://aka.ms/WATK-FreeTrial).
	If you have an existing account but need to enable the Windows Azure Mobile Services preview, see [Enable Windows Azure preview features](http://www.windowsazure.com/en-us/develop/mobile/tutorials/create-a-windows-azure-account/#enable).

[1]: http://www.microsoft.com/web/gallery/install.aspx?appid=IISExpress

<a name="Setup"/>
### Setup ###

In order to execute the exercises in this hands-on lab you need to set up your environment.

1. Open a Windows Explorer window and browse to the lab’s **Source** folder.

1. Execute the **Setup.cmd** file with Administrator privileges to launch the setup process that will configure your environment and install the Visual Studio code snippets for this lab.

1. If the User Account Control dialog is shown, confirm the action to proceed.

---
<a name="Exercises"/>
## Exercises ##

This hands-on lab includes the following exercises:

1. [Building Your First Windows Azure Application](#Exercise1)

Estimated time to complete this lab: **120** minutes.

<a name="Exercise1"></a>
### Exercise 1: Building Your First Windows Azure Application ###
