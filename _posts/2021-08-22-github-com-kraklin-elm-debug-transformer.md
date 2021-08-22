---
title: elm-debug-transformer
categories: ['typescript']
---
## [elm-debug-transformer](https://github.com/kraklin/elm-debug-transformer)

### Transform Elm Debug.log output into nice log object with custom formatter


Right now you can insert only alphabet characters and spaces as a Debug.log tag. 
```
-- this would parse successfuly
Debug.log "Some tag string" thingToPrintToConsole


-- this would NOT BE PARSED
Debug.log "Some String (with non [a-zA-Z] chars or numbers in it) " thingToPrintToConsole
```

This limitation is due to the problem recognizing arbitrary tag text from the rest of the types. I'm aware of that limitation and it is something that would be addressed in the upcoming versions. Thanks for understanding.

