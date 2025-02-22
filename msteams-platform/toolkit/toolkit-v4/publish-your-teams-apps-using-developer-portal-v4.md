---
title: Publish your Teams apps using Developer Portal v4
author: zyxiaoyuer
description: Learn how to integrate with Developer Portal in Teams Toolkit v4.
ms.author: zhany
ms.localizationpriority: medium
ms.topic: overview
ms.date: 07/29/2022
---

# Publish your Teams apps using Developer Portal v4

> [!IMPORTANT]
>
> We've introduced the Teams Toolkit v5 extension within Visual Studio Code. This version comes to you with many new app development features. We recommend that you use Teams Toolkit v5 for building your Teams app.
>
> [Teams Toolkit v4](~/toolkit/toolkit-v4/teams-toolkit-fundamentals-v4.md) extension will soon be deprecated.

You can configure and manage your app in Developer Portal within Teams Toolkit.

## To Publish app using Developer Portal

You can publish your app, which is created in Visual Studio and Visual Studio Code using Developer Portal:

# [Visual Studio Code](#tab/visualstudiocode)

The following are the steps to publish your app in Teams Developer Portal:

1. In **Teams Toolkit**, under **DEPLOYMENT** select **Developer Portal for Teams**.

    :::image type="content" source="images/dev-portal-ttk_1-v4.png" alt-text="Developer Portal for Teams":::

   Developer Portal opens in a browser.

1. Sign in to [Developer Portal for Teams](https://dev.teams.microsoft.com) using the corresponding account.
1. To import your app package in zip format, select **Apps** > **Import app**.

    :::image type="content" source="images/Select_Import_app-v4.png" alt-text="Select Import app":::

1. Select **Publish** > **Publish to your org**.

    :::image type="content" source="images/select_publish_1_v4.png" alt-text="Select to publish the app to your organization.":::

# [Visual Studio](#tab/visualstudio)

The following are the steps to publish your app in Teams Developer Portal:

1. Select **Project** > **Teams Toolkit** > **Open Teams Developer Portal to Publish**.

    :::image type="content" source="images/tdp-vs-v4.png" alt-text="Screenshot shows you how to open developer portal from visual studio.":::

1. Select the app package.

1. Teams Toolkit opens your app in **Teams Developer Portal** and direct you to the **Publish to your org** page, from there you can select **Publish your app** to continue with your publishing process.

    :::image type="content" source="images/vs-tdp-v4.png" alt-text="Screenshot shows you the app open in Teams Developer Portal.":::

---

## To update Manifest file and app package

If there are any changes related to Teams app's manifest file, you can update the manifest and publish the Teams app again. To publish Teams app manually, you can use [Developer Portal for Teams](https://dev.teams.microsoft.com/home).

1. Sign in to [Developer Portal for Teams](https://dev.teams.microsoft.com) using the corresponding account.
1. Select **Apps** > **Import app** to import your app package in zip format.<br>
   You need to replace the app, that you previously uploaded to the Developer Portal.
1. Select **Publish** > **Publish to your org**.

You can do the following configuration for your app in the Developer Portal:

* **Basic information**: This section shows and allows you to edit the **App names**, **App ID**, **Descriptions**, **Version**, **Developer information**, **App URLs**, **Application (client) ID**, and **Microsoft Partner Network ID**.
* **Branding**: This section allows you to add **Color icon** and **Outline icon** in `.png` format.
* **App features**: This section allows you to add the following features to your app:
  * Personal app
  * Bot
  * Connector
  * Scene
  * Group and channel app
  * Messaging extension
  * Meeting extension
  * Activity feed notification
* **Permissions**: This section allows you to give **Device permissions**, **Team Permissions**, **Chat/Meeting Permissions**, and **User Permissions** for your app.
* **Single sign-on**: This section allows you to configure your app to authenticate users with single sign-on (SSO) and to specify your app's resource for getting authorization tokens.
* **Languages**: This section allows you to set up or change the language of your app.
* **Domain**: This section allows you to add the domains to load your apps in the Teams client, such as *.example.com.

## See also

* [Teams Toolkit Overview](teams-toolkit-fundamentals-v4.md)
* [Developer Portal for Teams](~/concepts/build-and-test/teams-developer-portal.md)
* [Manage your apps in Developer Portal](~/concepts/build-and-test/manage-your-apps-in-developer-portal.md)
* [Develop your apps with Teams Toolkit](~/concepts/build-and-test/develop-your-apps-with-teams-toolkit.md)
