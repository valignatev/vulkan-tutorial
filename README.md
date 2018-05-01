# Vulkan Tutorial

I follow this tutorial: https://vulkan-tutorial.com/

My OS is Arch Linux, Makefile assumes that SDK version is [1.1.73.0](https://vulkan.lunarg.com/sdk/home#sdk/downloadConfirm/1.1.73.0/linux/vulkansdk-linux-x86_64-1.1.73.0.run).

Also, that SDK is installed one directory above the Makefile.

Tutorial also needs [GLM](https://github.com/g-truc/glm) and [GLFW](http://www.glfw.org):

```sh
sudo pacman -S glm glfw-x11
```

I also had to install vulkan driver for my intel GPU:

```sh
sudo pacman -S vulkan-intel
```

C++ skills and codestyle? Never heard about them :)
