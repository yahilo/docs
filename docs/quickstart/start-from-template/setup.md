---
title: Setup
sidebar_position: 1
---

To create composable apps/ [blocks](/docs/core-concepts/core#block), we definitely need some set of tools.

BB(Build with Blocks) CLI is used to create, collaborate, manage, and deploy blocks by connecting with Appblocks Registry(Blocks Store).

**Install BB CLI**
```
  npm i @appblocks/bb-cli -g
```
This will install our CLI globally.

```NOTE - Currently we only support in Linux/ Unix machines, including Mac.```

Hit bb To list see all the commands in CLI

**Connect Github and Appblocks**

To create a block make sure to log in to appblocks and connect with your GitHub account.

Use the below commands to do that
```
  bb login
```
Above command will open your default browser and ask you to authenticate CLI with your Appblocks Account. ( if you are not signed up yet signup option before login).
```
  bb connect github
```
This will open up the browser to authorize your CLI with your GitHub account. ( make sure to provide access to required organizations)

bb connect GitHub --force to forcefully authorize again.