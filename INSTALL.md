### JAVA1.8
refer to https://blog.csdn.net/lhmyy521125/article/details/99682471
java download link: https://www.oracle.com/technetwork/java/javase/downloads/index.html
download jdk-8u291-linux-x64.tar.gz (2021/06/07)

tar -zxvf jdk-8u291-linux-x64.tar.gz

vim ~/.bashrc
```
export JAVA_HOME=/your/path/to/jdk1.8.0_291
export JRE_HOME=${JAVA_HOME}/jre  
export CLASSPATH=.:${JAVA_HOME}/lib:${JRE_HOME}/lib  
export PATH=${JAVA_HOME}/bin:$PATH  
```
source ~/.bashrc
java -version

conda activate -n py38 python==3.8
pip install numpy