# Angular Firebase Authentication

![Angular Authentication Tutorial](https://s3.amazonaws.com/coursetro/posts/32-full.png)

Check out a demo here: [Angular Authentication Example](https://coursetro.com/preview/angular-auth-demo/)

Read (and watch) the tutorial here: [Angular Authentication Tutorial](https://coursetro.com/posts/code/32/Create-a-Full-Angular-Authentication-System-with-Firebase)

Clone this repo to get up and running! Check out more [Angular Tutorials](https://coursetro.com) at our site.





---

*Miscellany*

- The facebook config implementation wasn't tested
- Exported firebase configuration to firebase.credentials.ts and
  renamed firebaseConfigCredentials
- Add firebase.credentials.ts.empty, rename to firebase.credentials.ts
  and update with the credentials
- Add the firebase.credentials.ts file name to gitignore to keep
  credentials out of git repo
- chmod 600 firebase.credentials.ts


```
export const firebaseConfigCredentials = {
  apiKey: '',
  authDomain: '',
  databaseURL: '',
  storageBucket: '',
  messagingSenderId: ''
};
```

[forked to](https://github.com/davidwalter0/angular-auth-demo)
[fork from](https://github.com/designcourse/angular-auth-demo)
