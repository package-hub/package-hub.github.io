---
title: audio-wife
categories: ['java']
---
## [audio-wife](https://github.com/jaydeepw/audio-wife)

### A simple themable & integrable audio player library for Android.


AudioWife comes with a simple default player UI that you can use right away.
This is the simplest and fastest way to get AudioWife working.

```java
// mPlayerContainer = Parent view to add default player UI to.
AudioWife.getInstance().init(mContext, uri)
		.useDefaultUi(mPlayerContainer, getLayoutInflater());

```
