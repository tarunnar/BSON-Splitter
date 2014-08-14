# BSON Splitter

Split BSON(mongodump result) in many files of a fixed size.

# Last jar

[BSON Splitter Jar 0.1.0](https://github.com/alangalvino/BSON-Splitter/blob/develop/bson_splitter.jar)

# Dependencies

- Gradle

```
brew install gradle # for mac os
```

# Generating jar

Run command

```
gradle jar
```

Jar file will be in 'build/lib' folder

# Using jar

For split a file called 'backup.bson' in files of 100MB size run:

```
java jar bson_splitter.java backup.bson 100
```

Will generate files with name "splitted.number.bson", example: splitted.1.bson
