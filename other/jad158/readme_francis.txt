`jad -d /home/mingwei/souce -s java *.class`
-d后面跟的是反编译后文件存放的路径，-s java是反编译后的文件形式是.java 的，最后面是需要反编译的.class文件，支持通配符。
jad -o -r -s java -d ../source_java `com_413/**/*.class`
