---
id: is-approved
title: isApprovedAll
keywords: 
- 'plasma client, erc721, isApprovedAll, polygon, sdk'
description: 'Checks if all tokens are approved.'
---

`isApprovedAll` method checks if all tokens are approved. It returns boolean value.

```
const erc721Token = plasmaClient.erc721(<token address>, true);

const result = await erc721Token.isApprovedAll(<user Address>);

```
