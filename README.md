# FastDroid 

FastDroid is a taint analysis tool for android apps.
You can download a release jar file from here on Github.

##Instructions
If you want to use the command-line tool to run the data flow tracker, you can use the following command:

```
java -jar .../xd-fastdroid-jar-with-dependencies.jar  -Ftw  <path to the taint wrapper file>   
   -Fo < path to output file>  -Ffs   -a <APK File>  -p <Android JAR folder> -s <SourcesSinks file>
```

For finding out about the other options of the command-line tool, you can run the tool with the "-help" option 

### Configuration of FastDroid 

There are several options with which you can configure a tradeoff between performance and precision.

* ```-Flr <number>```  set a limite round of iterations of taint analysis. The default number is 10;
* ```-Ffs```  support the flow-sensitive. 
* ```-Fps``` support the path-sensitive. 
* ```-Fmd```  Fast mode which  make a tradeoff between performance and precision. 


## Contact

If you experience any issues, Please contact us
