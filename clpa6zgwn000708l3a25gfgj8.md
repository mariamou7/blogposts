---
title: "Make your first Dynamics 365 CRM Plugin without the “Power Platform Solution Template” Extension by Microsoft"
seoTitle: "Make your first Dynamics 365 CRM Plugin without the “Power Platform So"
seoDescription: "Develop a Microsoft Dynamics 365 CRM plugin without the “Power Platform Solution Template” Extension by Microsoft."
datePublished: Wed Nov 22 2023 20:03:18 GMT+0000 (Coordinated Universal Time)
cuid: clpa6zgwn000708l3a25gfgj8
slug: make-your-first-dynamics-365-crm-plugin-without-the-power-platform-solution-template-extension-by-microsoft
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1700683381085/08686391-c331-4483-b2af-93b1b67b6522.png
ogImage: https://cdn.hashnode.com/res/hashnode/image/upload/v1700683390606/5c6d75d7-d6b3-4abf-a062-f3a1e7982117.png
tags: microsoft, plugins, visual-studio, crm, dynamics365

---

# Intro

In the previous **Microsoft Business App** series article, we explored creating a plugin using the “**Power Platform Tools for VS 2022 Extension**” tool. However, it's worth noting that we can also develop a plugin **without this tool** in case it encounters any issues or isn't suited to our specific needs.

🧩 So let's get started!

# Requirements

You will need:

* Visual Studio 2019 or 2022
    
* .NET Framework 4.6.2
    
* Plugin Registration Tool
    

# Steps

## New Project

Open Visual Studio and press “Continue without code”.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1699468161589/72a751f7-1272-4156-9703-19acce6e8a4f.png align="left")

Search for “Class Library (**.NET Framework**)” and then choose it and press “Next”.

It's critical to select “Class Library (**.NET Framework**)” and not the basic “Class Library”.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1700680810091/8977900d-0a5d-4d52-a324-414d3c038a51.png align="center")

Give a proper “Project Name”, select “.NET Framework **4.6.2**” and press “Create”.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1700680926369/f144add3-2524-4d04-904b-a61f1f0305c7.png align="center")

Your solution is now ready and looks like this:

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1700681077612/d8ab6e17-68bf-4c23-9a49-4a4f8d8c6c59.png align="center")

### Microsoft.CrmSdk.CoreAssemblies NuGet Package

In Solution Explorer, right-click the name of the namespace and then press “Manage NuGet Packages...”.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1700681242589/df284c32-35ab-49a6-9c14-950119579037.png align="center")

There, press “Browse” and in the search bar write “Microsoft.CrmSdk.CoreAssemblies”.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1700681329997/41f6610d-9934-4d20-866a-d211b5c6429e.png align="center")

On the right panel, press “Install”.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1700681367576/ecb606c8-fac6-4cc1-9e75-3fd0553218d3.png align="center")

Once you are OK, you can click on Accept.

Next, you also get a chance to look at the licensing terms before you accept them.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1700681413532/5ae173da-4a99-42b6-a085-7e8fe347ebb9.png align="center")

## Signing

These steps are the same as you created the plugin with the “Power Platform Tools for VS 2022 Extension” tool.

So, right-click in the namespace and select “Properties”.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1700681523669/4c66e0a0-8a85-463c-a8a2-89bd17393645.png align="center")

Go to Signing, and tick the “Sign the assembly” check box.

Then select “&lt;New…&gt;”, give a name to the key file name, unselect the box for the password, and press “OK”.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1700681549536/b2c54f54-c56f-446e-8d83-faac569a7a6e.png align="center")

Ready!

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1700681560834/628fa54d-2ac7-48e5-9a90-8efff277cb82.png align="center")

## Building

Build the solution by right-clicking the Solution and selecting “Build Solution”.

## Plugin Registration Tool

To register the plug-in and the steps, download a helpful tool, the Plugin Registration Tool.

After signing in, select “Register” → “Register New …”.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1700681755377/9d0ef1c6-76ec-4687-b397-7a4ba8ad10a8.png align="center")

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1700681605501/6e64d4f0-2eb2-47b3-9b99-3ca69d3a6272.png align="center")

### New Assembly

Load the assembly you have created, mark the boxes, and press “Register Selected Plugins”.

# Closing

Now that you have the basics down, you are ready to start writing your code. Remember not to be afraid to experiment. The possibilities are endless!

Dive into the exciting world of Dynamics 365 CRM plugin development and unlock the platform's true power. Plugins are like the secret weapons of your CRM toolkit, letting you automate tasks, make CRM work your way, and connect it to other systems like a charm.

This guide has taken the mystery out of plugin development, giving you the knowledge and confidence to start building your own plugins. As you explore the wonders of Dynamics 365 CRM customization, you'll discover endless possibilities to tailor your CRM to your specific business needs.

If you have any questions or need help along your plugin development journey, don't hesitate to reach out. Happy coding, and get ready to transform your Dynamics 365 CRM experience! 👋