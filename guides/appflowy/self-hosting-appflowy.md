# ☁ Self-hosting AppFlowy with AppFlowy Cloud

AppFlowy is a privacy-first, open-source workspace designed for notes, wikis, projects, and more, giving you full control over your data and customizations. Over the past year, our community-driven approach has focused on delivering a data-privacy-centric, reliable native experience, and extensible platform.

We're thrilled to introduce self-hosting capabilities for AppFlowy, further empowering users to tailor workspaces to their needs. This guide is divided into two key sections:

1. Setting up AppFlowy Cloud on your server.
2. Building AppFlowy with a self-hosted server.

🙏If you have any questions, don't hesitate to contact us on [Discord](https://discord.gg/7kmZgcvA).

## Step 1: Setting Up AppFlowy Cloud

To self-host AppFlowy Cloud, please refer to our comprehensive [deployment guide](https://github.com/AppFlowy-IO/AppFlowy-Cloud/blob/main/doc/DEPLOYMENT.md).

## Step 2: Download the AppFlowy Application

To get started with the AppFlowy application, follow these steps:

1. **Download the Release Package**:
   * Access the latest release package from [AppFlowy Releases](https://github.com/AppFlowy-IO/AppFlowy-with-AppFlowy-Cloud-Build/releases).
2. **Launch and Configure the Application**:
   * After downloading, open the AppFlowy application.
   *   Click on 'Quick Start'.

       ![Quick Start](../assets/quick\_start.png)
   * Navigate to the `Settings` page.
   * On the left sidebar, select `Cloud Setting`.
   *   Choose `AppFlowy Cloud` as your cloud provider.

       ![Choose AppFlowy Cloud](../assets/choose\_appflowy\_cloud.png)
3. **Set Up Your Server**:
   * Enter your server address in the provided field.
   *   Click `Restart` to apply the changes.

       ![AppFlowy Cloud](../assets/fill\_appflowy\_cloud.png)
4. **Login**:
   * Go the `Setting` page
   *   On the left sidebar, select `User`.

       ![login.png](../assets/login\_page.png)

## Current Limitations

**Bundle ID Conflict**

The AppFlowy App built with AppFlowy Cloud currently shares the same bundle ID as the official AppFlowy App. Consequently, you cannot install both versions on the same device simultaneously. We are working on a solution for this issue.

**Ongoing Development of Stable Branch**

The process of building AppFlowy with AppFlowy Cloud using the stable branch is ongoing. Rapid developments and frequent updates in [AppFlowy Cloud](https://github.com/AppFlowy-IO/AppFlowy-Cloud) mean that new features are constantly being added.

**Collaborative Editing**

Currently, collaborative editing is not yet fully supported in the AppFlowy App when built with AppFlowy Cloud. Although collaborative editing data is synchronized across different devices via the AppFlowy Cloud server, the user interface does not instantly update with these synced changes. To see the latest data, you need to reopen the document or database. This feature is still in development.
