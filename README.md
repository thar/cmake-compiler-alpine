[![Docker Automated build](https://img.shields.io/docker/automated/thar/cmake-compiler-alpine.svg)](https://hub.docker.com/r/thar/cmake-compiler-alpine/)
[![Docker Pulls](https://img.shields.io/docker/pulls/thar/cmake-compiler-alpine.svg)](https://hub.docker.com/r/thar/cmake-compiler-alpine/)
[![Docker Stars](https://img.shields.io/docker/stars/thar/cmake-compiler-alpine.svg)](https://hub.docker.com/r/thar/cmake-compiler-alpine/) [![](https://images.microbadger.com/badges/image/thar/cmake-compiler-alpine.svg)](https://microbadger.com/images/thar/cmake-compiler-alpine "Get your own image badge on microbadger.com")

# cmake-compiler-alpine
Docker image to compile c++ cmake based projects

Prepare your compile/test script within your project and run:

```
docker run -v <project_folder>:/app thar/cmake-compiler-alpine ./<your_script.sh>
```
 