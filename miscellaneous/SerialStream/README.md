# Serial Port Stream Sample


This sample show how to use escpos-coffee with serial port stream.

It uses the jSerialComm dependency


you need to include it in your pom:
```xml
<dependency>
    <groupId>com.fazecast</groupId>
    <artifactId>jSerialComm</artifactId>
    <version>2.5.3</version>
</dependency>
```


##### 1. Edit Information about the port to be used on Principal.java
```java
    public static void main(String[] args) throws IOException {
        Principal obj = new Principal();
        obj.fnc1("com1"); // CHANGE HERE

```

##### 2. Compile and run
```shell script
mvn clean package
java -jar java -jar target\SerialStream-4.0.1-jar-with-dependencies.jar
```

## Third Party license
Details of license on [3RD_PARTY_LICENSE](3RD_PARTY_LICENSE.md) 





