---
title: react-native-contacts
categories: ['java', 'react-native', 'react-native-component']
---
## [react-native-contacts](https://github.com/morenoh149/react-native-contacts)

### React Native Contacts

`getAll` is a database intensive process, and can take a long time to complete depending on the size of the contacts list. Because of this, it is recommended you access the `getAll` method before it is needed, and cache the results for future use.
```js
import Contacts from 'react-native-contacts';

Contacts.getAll().then(contacts => {
  // contacts returned
})
```
See the full [API](#api) for more methods.
