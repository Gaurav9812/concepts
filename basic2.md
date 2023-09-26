**What is bundlers?**(Webpack, parcel, vite)
Make code production ready.

**What is `NPM`?**
Npm is a package manager. 

**What is `Parcel/Webpack`? Why do we need it?**


**What is `.parcel-cache`**
 Parcel caches everything it builds to disk. If you restart the dev server, Parcel will only rebuild files that have changed since the last time it ran. Parcel automatically tracks all of the files, configuration, plugins, and dev dependencies that are involved in your build, and granularly invalidates the cache when something changes. For example, if you change a configuration file, all of the source files that rely on that configuration will be rebuilt.

By default, the cache is stored in the .parcel-cache folder inside your project. 


**What is `npx` ?**
  Execute using npm.

**What is difference between `dependencies` vs `devDependencies`** 
  Dependencies are which we need in our server in production. like react
  dev-dependencies are those which we need only in our development server. like parcel

 **What is Tree Shaking?**
 Remove unwanted code. Suppose a library give us 20 functions but we use only 2 functions so parcel ignores rest of the functions, that we don't use.

**What is Hot Module Replacement?**
  Parcel reload everytime you make some changes in file with the help of File watcher. File watcher algorithm is written in C++. who watches our file and whenever something changes it  tels server to reload.


**List down your favourite 5 superpowers of Parcel and describe any 3 of them in your own words.**

**What is `.gitignore`? What should we add and not add into it?**
 This contains the files or directory that git ignores and dosn't put it in git. Anything which we can generate on server should be put in git ignore.

**What is the difference between `package.json` and `package-lock.json`**
  package-lock.json locks the package. Never put in gitignore

**Why should I not modify `package-lock.json`?** 

**What is `node_modules` ? Is it a good idea to push that on git?**

**What is the `dist` folder?**
It contains build

**What is `browserlists`**
Make our code compatible for all browsers.

  Read about dif bundlers: vite, webpack, parcel

**Read about: ^ - caret and ~ - tilda**
3.9.2 => 3 Major , 9 minor and 2 patch
  So if you see ~1.0.2 it means to install version 1.0.2 or the latest patch version such as 1.0.4
  If you see ^1.0.2 it means to install version 1.0.2 or the latest minor or patch version such as 1.1.0.

**Read about Script types in html (MDN Docs)**

**What is Transistive dependencies?**
Dependencies which are dependencies of another dependencies are known as transistive dependencies.