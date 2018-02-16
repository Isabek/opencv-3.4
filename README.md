# opencv-3.4
Docker Image for OpenCV 3.4

This image contains OpenCV 3.4 for C++ and cppkafka.

### Using with Docker Compose

```yml
version: '3.5'
services:
  service1:
      image: isabek/opencv-3.4
      stdin_open: true
      tty: true
```
