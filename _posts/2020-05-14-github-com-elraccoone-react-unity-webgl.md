---
title: react-unity-webgl
categories: ['typescript', 'react', 'unity']
---
## [react-unity-webgl](https://github.com/elraccoone/react-unity-webgl)

### React Unity WebGL provides an easy solution for embedding Unity WebGL builds in your React application, with two-way communication between your React and Unity application with advanced API's.


Install using npm for your JavaScript (babel) and TypeScript React Project. Make sure you download the release matching with your Unity version. I try to update this plugin in case of need as fast as possible. For the corresponding, check the releases on [GitHub](https://github.com/elraccoone/react-unity-webgl/releases) or [NPM](https://www.npmjs.com/package/react-unity-webgl).

**IMPORTANT NOTE** Since development and maintaining this modules takes a lot of time and Unity [decided](https://forum.unity.com/threads/changes-to-the-webgl-loader-and-templates-introduced-in-unity-2020-1.817698/) to change their entire system of how WebGL builds work. I've decided to drop support for every Unity below 2020.1 from version `8.0.0`. If your project in build with this version of Unity, please either upgrade your project, or use version `7.x.x` of the React Unity WebGL package. I will release patches for Unity LTS builds, but since Unity rarely makes any big changes in their LTS builds, I do not expect to have to publish any patches. Development takes a lot of time, if you're using this module for production, please consider donating to support the project. You can follow the development `8.0.0` in this [issue](https://github.com/elraccoone/react-unity-webgl/issues/96). Thank you! 

```sh
$ npm install react-unity-webgl
```
