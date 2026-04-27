---
title: Working in Workspace
---

A Workspace is a folder on your computer.
Click “Add Workspace,” on the sidebar, select a folder on your computer to add it.
In the selector at the bottom of the input box, choose which Workspace the new chat should be based on
(or select ‘Playground’ or “Explore,” which means working outside of any Workspace; you can also select a folder—see [here](/optic/use-optic#manage-chats)).

Within a Workspace, the Agent can interact with files in the corresponding folder.
Additionally, the Workspace feature creates a `.opticlm` folder within the folder,
where Optic stores some of the information it reads, including a configuration file `.opticlm/config.json`.
The contents of this configuration file will **append to or override** the global configuration file.

In Workspace, you can connect extensions such as the VSCode code editor,
the Obsidian note-taking app, or an LSP language server.
These features are currently experimental.
