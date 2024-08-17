---
layout: post
title: Installing and Configuring Simple Voice Chat
category: Modifications
tags: Mods
permalink: minecraft/modifications/mods/voice-chat
description: Adding a proximity-based voice chat to your server.
author:
    - Naoki
    - Deka
    - Mocab

icon: "https://cdn.modrinth.com/data/9eGKb6K1/icon.png"
mod-name: Simple Voice Chat
mod-author: henkelmax
mod-url: "https://modrinth.com/plugin/simple-voice-chat"
---

## :studio_microphone: What Is Simple Voice Chat?

Simple Voice Chat is a plugin and mod that introduces proximity-based voice chat. It allows players to communicate with each other in-game. It also has a variety of addons that offer additional features. Simple Voice Chat requires you to have the mod installed on your client, which is only available on the Java Edition of Minecraft. If you don't have it installed on your client, you can still join the server, but you won't be able to use the voice chat features.

## :hammer_and_wrench: Installation and Configuration:

### Prerequisites:

-   Ensure your server is running with either Fabric or Forge or any of their forks (Quilt & NeoForge respectively).
-   Your server must have at least one **unused** extra port or in other words, a forwarded port. If you wish to allocate an extra port, please follow our [extra ports](/falix/dashboard/server/extra-port) guide.
-   Make sure players have the mod installed locally.

### Installation:

1. Log into the [Dashboard](https://client.falixnodes.net/).

2. Choose a server within your server list.

3. You will be redirected to your server's [Console](https://client.falixnodes.net/server/console) page. In the top navigation bar, hover over "Manage", then navigate to the [File Manager](https://client.falixnodes.net/server/filemanager).

4. Locate and open the [mods](https://client.falixnodes.net/server/filemanager?dir=/mods/) folder.

5. Download the mod from the official [download](https://modrinth.com/plugin/simple-voice-chat/versions) page. Make sure to select the version and mod loader matching your server.

6. In the Dashboard, click on "Upload Files".

7. Locate the downloaded mod and select it, then upload it to your server.

8. (Re)start your server to enable the mod.

## Configuration:

1. Once again, navigate back to the [File Manager](https://client.falixnodes.net/server/filemanager) by hovering over "Manage", then clicking on "File Manager".

2. Locate and open the [config](https://client.falixnodes.net/server/filemanager?dir=/config/) folder.

3. A new folder called [voicechat](https://client.falixnodes.net/server/filemanager?dir=/config/voicechat/) should have generated. Open it to access the newly generated configuration files.

4. Find and open "voicechat-server.properties". This is the main configuration file where you will be able to customize any feature needed.

5. Look for the `port=` setting and set it to your server's **unused** extra port. This will be the port your voice chat will be hosted on.

    > If you require assistance creating or finding your extra ports, refer to our [extra ports](/falix/dashboard/server/extra-port) guide.

6. Click on "Save File" to save your changes.

7. (Re)start your server to apply the changes.