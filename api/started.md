---
title: Getting Started
description: Mermaids API - Getting Started
parent: Mermaids API
layout: page
permalink: /api/getting-started/
nav_order: 1
---

### First add Mermaids to your Project:

Maven `pom.xml`:
```
<dependencies>
    <dependency>
        <groupId>plugin.siren</groupId>
        <artifactId>Mermaids</artifactId>
        <version>1.4.0</version>
        <scope>provided</scope>
        <optional>true</optional>
    </dependency>
</dependencies>
```

Gradle `build.gradle`: (untested)
```
dependencies {
    compileOnly 'plugin.siren:Mermaids:1.4.0'
}
```
<br/>

### Next, update the Hytale manifest:

Optional Dependency `manifest.json`:
```json5
"OptionalDependencies": {
  "Siren:Mermaids": "*"
}
```

Required Dependency `manifest.json`:
```json5
"Dependencies": {
  "Siren:Mermaids": "*"
}
```