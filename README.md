
# Android Docker image

[![Docker build](https://img.shields.io/docker/automated/mikangali/android.svg)]()

### Android 7 (SDK 25.X)

- Ant 1.9.6
- Maven 3.3.9
- Java 1.8.0_111
- Gradle 2.10 (Groovy 2.4.5)
- Android SDK 24.4.1
    + APIs: android-10,android-15,android-19,android-21,android-22,android-23,android-24,android-25
    + Build-Tools: 25.0.2

----
### Pull from Docker Hub
```
docker pull beevelop/android:latest
```

### Build from GitHub
```
docker build -t mikangali/android github.com/mikangali-docker/android
```

### Run image
```
docker run -it beevelop/android bash
```

### Use as base image
```Dockerfile
FROM mikangali/android:latest
```
