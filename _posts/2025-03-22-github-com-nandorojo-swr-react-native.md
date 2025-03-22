---
title: swr-react-native
categories: ['typescript']
---
## [swr-react-native](https://github.com/nandorojo/swr-react-native)

### React Native/React Navigation compatibility for Vercel's useSWR hook. 🐮


Add React Native + React Navigation compatibility to [`swr`](https://swr.vercel.app). 👨🏻‍🔧

```diff
- import useSWR from 'swr'
+ import useSWRNative from '@nandorojo/swr-react-native'
```

**That's it.**

SWR revalidation now works in your React Native app. Requests also revalidate when your React Navigation screens focus.
