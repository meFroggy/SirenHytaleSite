---
title: Functions
description: Mermaids API - Functions
parent: Mermaids API
layout: page
permalink: /api/functions/
nav_order: 1
---

| Function:                                                                                             | Return: | Description:                                             |
|:------------------------------------------------------------------------------------------------------|:--------|:---------------------------------------------------------|
| `MermaidsAPI.isMermaid(Store<EntityStore> store, Ref<EntityStore> ref)`                               | Boolean | Check to see if the reference is a mermaid.              |
| `MermaidsAPI.isUnderwater(Store<EntityStore> store, Ref<EntityStore> ref)`                            | Boolean | Check to see if the reference is underwater.             |
| `MermaidsAPI.isForcedMermaid(Store<EntityStore> store, Ref<EntityStore> ref)`                         | Boolean | Check to see if the reference is forced to be a mermaid. |
| `MermaidsAPI.setForcedMermaid(Store<EntityStore> store, Ref<EntityStore> ref, boolean forcedMermaid)` |         | Force the reference to be / not be a mermaid.            |