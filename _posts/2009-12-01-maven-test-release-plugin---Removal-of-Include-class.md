---
layout: post
title: maven-test-release-plugin - Removal of Include class
tags: [framework-1-124,maven-test-release-plugin]
---
<u>Context</u>:
Duplicated code has been found inside plugin (```Include``` class which duplicates the code from ```ArtifactDescriptor```).

<u>Description</u>:
```Include``` class has been removed.