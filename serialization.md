## Serialization in Java
Serialization is the process of converting an object into bytes, so that it can be transmitted over the network. Serialized object is an object represented as sequence of bytes that includes objects data, object type, and the types of data stored in the object.
### Main purpose of Serialization in Java
Communication: To pass an object over network by making remote procedure call.

Copying: We can create duplicates of original object by using byte array.
To distribute objects across different JVMs.

To implement serialization in java there is an interface defined in `java.io package` called serializable interface. `Java.io.Serializable` interface is a marker interface which does not contain any methods. A class implementing Serializable lets the JVM know that the instances of the class can be serialized. 

_Syntax_
```java
public interface Serializable {

 }
```
