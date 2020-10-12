## Hexabase Configuration

Starting with Hexabase class, it is used to initialize session to hexabase. by initializing this class, you can store api token to `sessionStorage` automatically, and use wide range variety of hexabase system.

## Configuration


```ts
// Initialize default app
// use your own/company credentials
import { Hexabase } from 'hexabase-sdk'

Hexabase.initializeApp({
    email: 'j.soliva@b-eee.com',    // registered user email address in Hexabase
    password: '123456'              // user password
})
```