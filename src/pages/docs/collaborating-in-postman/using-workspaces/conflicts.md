---
title: "Resolving team conflicts"
order: 80
updated: 2021-04-21
page_id: "conflicts"
contextual_links:
  - type: section
    name: "Prerequisites"
  - type: link
    name: "Grouping requests in collections"
    url: "/docs/sending-requests/intro-to-collections/"
  - type: link
    name: "Sharing your work"
    url: "/docs/collaborating-in-postman/sharing/"
  - type: section
    name: "Additional Resources"
  - type: subtitle
    name: "Related Blog Posts"
  - type: link
    name: "Forking + Merging: A Conflict Resolution Solution"
    url: "https://blog.postman.com/forking-merging-a-conflict-resolution-solution/"
  - type: section
    name: "Next Steps"
  - type: link
    name: "Troubleshooting requests"
    url: "/docs/sending-requests/troubleshooting-api-requests/"

warning: false
---

By syncing your Postman data with an account, you can work between devices and as part of a team. If a conflict occurs between the data in your local app and the data synced to the Postman servers, you will see a prompt allowing you to choose which version to preserve.

For example, if a teammate makes a change to the same request you are currently working on, and their change syncs to the Postman servers while you are editing yours, then you attempt to save your changes, a conflict may arise.

If Postman encounters a conflict between your local app and the synced data for your account or team, you will see the __Resolve Sync Conflicts__ modal when your account attempts to sync.

<img alt="Sync Conflicts" src="https://assets.postman.com/postman-docs/sync-conflicts-v8.jpg" width="600px"/>

You will see a tab for each collection affected by conflicts, and each conflict listed indicating the difference between the local and server version.

You can choose to preserve your local changes, or update your local version to match the synced version from the server. You will see an overview of each conflict and can choose __Local changes__ or __Server changes__ for each one.

After you choose which version to use, select __Resolve Conflicts__ to update both your local version and the synced version of the projects you're working on. You will need to make selections for every collection affected and select __Resolve Conflicts__ to update each one. If you choose your local changes, other devices and team members will now see your changes whenever Postman syncs for them.

If you update the conflict selections and want to revert to the original selections, which will be to use the server changes by default, select __Reset__.

## Next steps

You can use [version control](/docs/collaborating-in-postman/version-control-for-collections/) on your collections to manage changes within a team, for example by creating forks and opening pull requests to merge your changes.
