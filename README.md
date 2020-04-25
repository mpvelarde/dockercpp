# Run cpp in docker container with VS Code

Loosely based on [Build C++ Applications in a Linux Docker Container with Visual Studio](https://devblogs.microsoft.com/cppblog/build-c-applications-in-a-linux-docker-container-with-visual-studio/) and [Developing inside a Container](https://code.visualstudio.com/docs/remote/containers)

## Requirements
Requirements are listed in [Developing inside a Container](https://code.visualstudio.com/docs/remote/containers)

## Open project in container

Pull Ubuntu base container
```
> docker pull ubuntu
```

Open VS Code and from command list choose
```
Remote-Containers: Open Folder in Container
```

## Build & Run
```
> mkdir build && cd build
> make ../ &&  make
> ./helloworld
```