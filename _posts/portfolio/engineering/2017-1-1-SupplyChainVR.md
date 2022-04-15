---
layout: media
title: Network visualizer VR 
categories: portfolio
excerpt: Exploratory project to visualize actual supply chain network data in VR.
tags: engineering
image:
 teaser: teaser/teaser-supplychainvr.jpg
yeartitle: 2016
---

I collaborated with Dr. Alexandra Brintup on this exploratory project to visualize real-world supply chain network data in VR. The software was developed using Unity which rendered the network data through a JSON file. The project arises from a need to intuitively visualize complex supply chain network data. An intuitive visualization of how a supply chain is setup would enable top management to make more informed decisions.

The prototype largely works but there were a few issues with it. We found that performance is impacted when attempting to render all the nodes in the network. Rendering thousands of nodes in 3D-space for VR consumption is a bit intense to put it lightly. For the prototype, we had to artifically reduce the number of layers of suppliers in our network to maintain framerate at a comfortable level. In hindsight, perhaps creating different level of details (LOD) could potentially minimize the rendering load. The other issue is with the navigation interface. As it were, you would use the VR controllers to fly around in 3D-space to explore the network. This is fine for a short while but extended usage is definitely uncomfortable as the motion in VR would quickly lead to cyber-sickness.

Still a pretty cool project nonetheless. We managed to demo it to industry figures such as the CEO of Cisco UK.

![supply chain vr cisco]({{ site.baseurl }}/images/portfolio/portfolio-supplychainvr1.jpg)

<iframe width="560" height="315" src="https://www.youtube.com/embed/yCp0aCdyA00" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>