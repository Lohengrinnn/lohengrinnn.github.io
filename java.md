### Jdk install

When execute "java xx.jar", console output: "No Java runtime present, requesting install." and popup dialog prompt to install JDK

1.  local java in mac
   ls -l /usr/bin/java
   lrwxr-xr-x  1 root  wheel  74 Oct  8 13:44 /usr/bin/java -> /System/Library/Frameworks/JavaVM.framework/Versions/Current/Commands/java

2. jdk in intellij
   File -> Project Structure -> Platform Settings -> SDKs
   11: /Applications/IntelliJ IDEA CE.app/Contents/jbr/Contents/Home

3. $JAVA_HOME is empty.
   try to set JAVA_HOME to intellij's JDK
   export JAVA_HOME="/Applications/IntelliJ IDEA CE.app/Contents/jbr/Contents/Home"

it works

### build jar:

https://blog.csdn.net/weixin_36210698/article/details/80850397

