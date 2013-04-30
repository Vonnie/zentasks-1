# ZenTasks Tutorial

### Java Version (2.1.1)


I have decided to take the time to learn the Play! Framework inside and out as I now have some time. I will store my source code here from the `ZenTasks` tutorial provided in the [Documentation](http://www.playframework.com/documentation/2.1.1/JavaGuide1) section for Java on the Play! site.

#### .gitignore File Contents

```
logs
project/project
project/target
target
tmp
.history
dist
/.idea
/*.iml
/out
/.idea_modules
/.classpath
/.project
/RUNNING_PID
/.settings
```

### My Dev Stack:

- MacBook Pro Retina Display (15")
- JDK 1.7.0_21 for Mac OS X 
- Sublime Text 2 with Play! support
- IntelliJ 12.1.2 Utlimate with Play! 2 support
- 2 x 27" Dell IPS Displays
- Play! 2.1.1
- Editor color scheme is Tomorrow Night for both Sublime and Idea with Source Code Pro font.

### Other Stuff

I dislike always having to apply migrations so I use the optional:

`-DapplyEvolutions.default=true` when I run the `play` command. It seems minor but every little thing you can do to save a few seconds of development time helps.
