---
title: networked-aframe
categories: ['javascript', 'aframe', 'webrtc']
---
## [networked-aframe](https://github.com/networked-aframe/networked-aframe)

### A web framework for building multi-user virtual reality experiences.


Networked-Aframe works by syncing entities and their components to connected users. To connect to a room you need to add the [`networked-scene`](#scene-component) component to the `a-scene` element. For an entity to be synced, add the `networked` component to it. By default the `position` and `rotation` components are synced, but if you want to sync other components or child components you need to define a [schema](#syncing-custom-components). For more advanced control over the network messages see the sections on [Broadcasting Custom Messages](#sending-custom-messages) and [Options](#options).

