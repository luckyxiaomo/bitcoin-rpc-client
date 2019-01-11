bitcoin-rpc-client
==================

This is a lightweight java bitcoind JSON-RPC client binding. It does not require any external dependencies.

Maven
=====
The package is published in the wf.bitcoin group and you can add it to you pom.xml adding a section like this:

```
<dependency>
    <groupId>wf.bitcoin</groupId>
    <artifactId>bitcoin-rpc-client</artifactId>
    <version>1.1.0</version>
</dependency>
```

Now
=====
The package not published

```
<dependency>
    <groupId>lk.bitcoin</groupId>
    <artifactId>bitcoin-rpc-client</artifactId>
    <version>2.0.0</version>
</dependency>
```


```
mvn install:install-file -Dfile=<the file path>  -DgroupId=lk.bitcoin -DartifactId=bitcoin-rpc-client -Dversion=2.0.0 -Dpackaging=jar
```