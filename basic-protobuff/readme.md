# Basic Protocol Buffer Serialization/Deserialization in java

##How to setup
### Prerequisite
The following software should be preinstalled in your machine.
* [protocol buffer compiler](https://github.com/protocolbuffers/protobuf/releases)
* [jdk1.8+](https://openjdk.java.net/install/)

### How To Build
run following
```shell
cd $project_dir
protoc --java_out=src/main/java/ src/main/resources/addressbook.proto
./gradlew clean build
```

`AddPerson` class show how we can serialize it and `ListPeople` class show how we can deserialize it back. 