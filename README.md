
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

https://www.oracle.com/technetwork/java/javase/downloads/index.html
https://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html



### Create Hello World Program

```
vim Hello.java
```

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


### Exectute Program 

```
java Hello
```