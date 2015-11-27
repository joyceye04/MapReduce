# MapReduce
this repository includes problems solved by MapReduce


## How to use

### Create jar
javac -classpath $HADOOP_CLASSPATH -d [target-dir] [javaname].java

jar -cvf [jarpath]/[jarname].jar -C [classpath]/ .

### Run in hadoop
hadoop jar [jarname].jar [classname] [inputpath/text.txt] [output]