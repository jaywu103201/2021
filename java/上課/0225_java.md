```

C:\Users\KSUIE>javac
Usage: javac <options> <source files>
where possible options include:
  @<filename>                  Read options and filenames from file
  -Akey[=value]                Options to pass to annotation processors
  --add-modules <module>(,<module>)*
        Root modules to resolve in addition to the initial modules, or all modules
        on the module path if <module> is ALL-MODULE-PATH.
  --boot-class-path <path>, -bootclasspath <path>
        Override location of bootstrap class files
  --class-path <path>, -classpath <path>, -cp <path>
        Specify where to find user class files and annotation processors
  -d <directory>               Specify where to place generated class files
  -deprecation
        Output source locations where deprecated APIs are used
  --enable-preview
        Enable preview language features. To be used in conjunction with either -source or --release.
  -encoding <encoding>         Specify character encoding used by source files
  -endorseddirs <dirs>         Override location of endorsed standards path
  -extdirs <dirs>              Override location of installed extensions
  -g                           Generate all debugging info
  -g:{lines,vars,source}       Generate only some debugging info
  -g:none                      Generate no debugging info
  -h <directory>
        Specify where to place generated native header files
  --help, -help, -?            Print this help message
  --help-extra, -X             Print help on extra options
  -implicit:{none,class}
        Specify whether or not to generate class files for implicitly referenced files
  -J<flag>                     Pass <flag> directly to the runtime system
  --limit-modules <module>(,<module>)*
        Limit the universe of observable modules
  --module <module>(,<module>)*, -m <module>(,<module>)*
        Compile only the specified module(s), check timestamps
  --module-path <path>, -p <path>
        Specify where to find application modules
  --module-source-path <module-source-path>
        Specify where to find input source files for multiple modules
  --module-version <version>
        Specify version of modules that are being compiled
  -nowarn                      Generate no warnings
  -parameters
        Generate metadata for reflection on method parameters
  -proc:{none,only}
        Control whether annotation processing and/or compilation is done.
  -processor <class1>[,<class2>,<class3>...]
        Names of the annotation processors to run; bypasses default discovery process
  --processor-module-path <path>
        Specify a module path where to find annotation processors
  --processor-path <path>, -processorpath <path>
        Specify where to find annotation processors
  -profile <profile>
        Check that API used is available in the specified profile
  --release <release>
        Compile for the specified Java SE release. Supported releases: 7, 8, 9, 10, 11, 12, 13, 14, 15
  -s <directory>               Specify where to place generated source files
  --source <release>, -source <release>
        Provide source compatibility with the specified Java SE release. Supported releases: 7, 8, 9, 10, 11, 12, 13, 14, 15
  --source-path <path>, -sourcepath <path>
        Specify where to find input source files
  --system <jdk>|none          Override location of system modules
  --target <release>, -target <release>
        Generate class files suitable for the specified Java SE release. Supported releases: 7, 8, 9, 10, 11, 12, 13, 14, 15
  --upgrade-module-path <path>
        Override location of upgradeable modules
  -verbose                     Output messages about what the compiler is doing
  --version, -version          Version information
  -Werror                      Terminate compilation if warnings occur


C:\Users\KSUIE>
```
```
C:\>cd /d d:\test

d:\test>cd/

d:\>
d:\>cd HelloWorld2
系統找不到指定的路徑。

d:\>cd HelloWorld2.java
系統找不到指定的路徑。

d:\>cd 4090E036

d:\4090E036>HelloWorld2.java

d:\4090E036>dir
 磁碟區 D 中的磁碟沒有標籤。
 磁碟區序號:  6839-C000

 d:\4090E036 的目錄

2021/02/25  下午 02:39    <DIR>          .
2021/02/25  下午 02:39    <DIR>          ..
2021/02/25  下午 02:39               127 HelloWorld.java
2021/02/25  下午 02:45               202 HelloWorld2.java
2021/02/25  下午 02:46               205 HelloWorld21.java
               3 個檔案             534 位元組
               2 個目錄  10,183,442,432 位元組可用
```
### println()和print()有何差別?

```
public class HelloWorld2{

     public static void main(String []args){
        System.out.print("Hello ");
	System.out.print("Mydeargreatteacher");
	System.out.println("Hello World");
     }
}
```
```
d:\4090E036>java HelloWorld2.java
Hello MydeargreatteacherHello World
```
```
public class HelloWorld21{

     public static void main(String []args){
        System.out.print("Hello ");
	System.out.println("Mydeargreatteacher");
	System.out.println("Hello World");
     }
}
```
```
d:\4090E036>java HelloWorld21.java
Hello Mydeargreatteacher
Hello World

d:\4090E036>
```
