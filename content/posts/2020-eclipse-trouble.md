---
title: Eclipse Trouble
date: 2020-10-02T07:26:54.670Z
draft: false
toc: false
categories:
  - school
author: Nick Heymans
---
I tried to start eclipse to do some java programming but i kept getting this error:

```
"A Java Runtime Environment (JRE) or Java Development Kit (JDK)
must be available in order to run Eclipse.
No Java virtual machine was found after searching the following locations:
C:\Program Files\eclipse\jre\bin\javaw.exe
javaw.exe in your current PATH
```

So after trying to update windows, and checking that the required files were actually there, i found this [forum post](https://stackoverflow.com/questions/12426810/eclipse-wont-start-no-java-virtual-machine-was-found).

The solution was simple:
- open the ecipse.ini file
- add this line of code (change the file path so it points to your jdk\bin folder)
  ``` 
  C:\Program Files\Java\jdk-14.0.2\bin\
  ```
- save the file




