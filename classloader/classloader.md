## ClassLoader Class Diagram
![classloader](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/oka96/java/master/classloader/classloader.wsd)

## ClassLoader
1. BootstrapClassLoader
> it's part of jvm, and not java class
2. ExtClassLoader
3. AppClassLoader

we can check all the java classes load by which classLoader
#### Take note
`null` ->  `BootstrapClassLoader`

#### Parent ClassLoader
Parent ClassLoader does not mean parent-child class relationship