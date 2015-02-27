---
layout: post
title: CornerPin3D.nk
published: true
category: nodes
tags: 2.5D
---

### Intro
- card3D alternative (realtime), but has stabalize, matchmove, project, and concatination & roto control passthrough like a cornerPin node

### Details
- "originalAuthor": "Rafal Kaniewski"
- "dateCreated": "01/01/2015"
- "status": "beta"
- "source": "https://github.com/cardPlane/"
- "Licence": "[https://github.com/openNuke/toolset/blob/master/LICENCE]"

### Note
BETA!!
Although this tool achieves creating a cornerpin node driven by a camera and card (i.e. a concatinating, roto control pass through that can be frame offset and inverted) it has some bugs that I think are due to the reconcile3D node.

KNOWN BUGS:
1) On some farms it sometimes misscalculates the odd frame so it has to be baked and that suks.
2) It takes ages to load into nuke (like x50 longer) so it must be bugging out, even though no errors are reported.

TODO REQUESTS:
1) have the camera piped in
2) have a axis connection/input? for an offset for the card.
3) have a look at function

### Instructions
Please request someone to contribute instructions in comments below.
