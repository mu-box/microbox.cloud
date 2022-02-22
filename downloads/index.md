---
layout: default
title: Downloads
download: "![Download](/assets/images/download.png)"
missing: "![Not Available](/assets/images/missing.png)"
---
# Microbox Downloads

> **Warning!** These installers provide Microbox, which is still in early Alpha stages. While Microbox is based on Nanobox, and in fact the tools available here are forked from the original Nanobox tools, not all Nanobox features are currently supported under the new names and namespaces. For the moment, there are no guarantees that anything will actually work, until we have a chance to properly implement the missing features.
>
> Thanks for your understanding!

Below you'll find the various available installers for the Microbox local tools. Supported OS/architecture combinations are the same as the ones for Docker itself; please contact them about supporting new hosts, as we'd love to support more!

| OS                 |                                  amd64                                   |                      amd64 + VirtualBox (DEPRECATED)                      |                                  arm64                                   |                                  arm                                   |                                  s390x                                   |
|:-------------------|:------------------------------------------------------------------------:|:-------------------------------------------------------------------------:|:------------------------------------------------------------------------:|:----------------------------------------------------------------------:|:------------------------------------------------------------------------:|
| Windows            |    [{{ page.download }}]({{ site.data.downloads.windows.amd64.url }})    | [{{ page.download }}]({{ site.data.downloads.windows.amd64_bundle.url }}) |                            {{ page.missing }}                            |                           {{ page.missing }}                           |                            {{ page.missing }}                            |
| macOS              |    [{{ page.download }}]({{ site.data.downloads.mac.universal.url }})    |   [{{ page.download }}]({{ site.data.downloads.mac.amd64_bundle.url }})   |    [{{ page.download }}]({{ site.data.downloads.mac.universal.url }})    |                           {{ page.missing }}                           |                            {{ page.missing }}                            |
| Arch Linux         |  [{{ page.download }}]({{ site.data.downloads.linux.arch.amd64.url }})   |                            {{ page.missing }}                             |                            {{ page.missing }}                            |                           {{ page.missing }}                           |                            {{ page.missing }}                            |
| CentOS/RHEL/Fedora | [{{ page.download }}]({{ site.data.downloads.linux.centos.amd64.url }})  |                            {{ page.missing }}                             | [{{ page.download }}]({{ site.data.downloads.linux.centos.arm64.url }})  |                           {{ page.missing }}                           | [{{ page.download }}]({{ site.data.downloads.linux.centos.s390x.url }})  |
| Debian/Ubuntu      | [{{ page.download }}]({{ site.data.downloads.linux.debian.amd64.url }})  |                            {{ page.missing }}                             | [{{ page.download }}]({{ site.data.downloads.linux.debian.arm64.url }})  | [{{ page.download }}]({{ site.data.downloads.linux.debian.arm.url }})  | [{{ page.download }}]({{ site.data.downloads.linux.debian.s390x.url }})  |
| Generic Linux      | [{{ page.download }}]({{ site.data.downloads.linux.generic.amd64.url }}) |                            {{ page.missing }}                             | [{{ page.download }}]({{ site.data.downloads.linux.generic.arm64.url }}) | [{{ page.download }}]({{ site.data.downloads.linux.generic.arm.url }}) | [{{ page.download }}]({{ site.data.downloads.linux.generic.s390x.url }}) |

Icons by Tomas Knopp via the Noun Project
