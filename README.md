
# Android Docker image

[![Docker Automated buil](https://img.shields.io/docker/automated/mikangali/android.svg)](https://hub.docker.com/r/mikangali/android)

### Android (SDK tools)

- Koltin 1.3.11
- Gradle 4.10.3
- Java openjdk-8-jdk
- Android SDK 4333796

### Pull from Docker Hub

```
docker pull mikangali/android:latest
```

### Build from GitHub

```
docker build -t mikangali/android github.com/mikangali-docker/android
```

### Run image

```
docker run -it mikangali/android bash
```

### Use as base image

```Dockerfile
FROM mikangali/android:latest

...

```

### Links

* Inspired by : https://github.com/thyrlian/AndroidSDK
