
### Check Java Installation

```
which java
which javac 
```

### Check Java Version

```
java -version
javac -version
```

### Install Java 

* [Downloads Index](https://www.oracle.com/technetwork/java/javase/downloads/index.html)
* [JDK 8 Direct Links](https://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)


### Create Hello World Program

Create a file called Hello.java.
```
touch Hello.java
```

Edit Hello.java with vim or nano so that it contains the code below.
```java
public class Hello {
        public static void main(String[] args) {
                System.out.println("Hello Java!");
        }
}
```

### Compile Program Into ByteCode

```
javac Hello.java
```


### Execute Program 

```
java Hello
```
