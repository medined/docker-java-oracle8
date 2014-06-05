
# Build the image

```
docker build -t medined/java-oracle8 .
```

# See the image

```
docker images
```

# Run the image

```
docker run -i -t medined/java-oracle8 /bin/bash
```

# Validate Java version inside image

```
java version "1.8.0_05"
Java(TM) SE Runtime Environment (build 1.8.0_05-b13)
Java HotSpot(TM) 64-Bit Server VM (build 25.5-b02, mixed mode)
```
