1.download apache thrift 
http://thrift.apache.org/

2.build and install the apache thrift compiler and libraries

Apache Thrift's compiler is written in C++ and designed to be portable, 
but there are some system requirements which must be installed prior to use.

也可直接下载compiler
http://thrift.apache.org/download
thrift-0.9.2.exe

3.write a thrift file ，and then compile

thrift-0.9.2.exe  -r --gen java tutorial.thrift

在目录gen-java 下可找到生成的java源代码

4.copy出 F:\projects\org.apache\Thrift\thrift-0.9.2\lib\java 下代码加入project

可从build.properties文件找到 lib 包依赖
httpclient.version=4.2.5
httpcore.version=4.2.4
slf4j.version=1.5.8
servlet.version=2.5




