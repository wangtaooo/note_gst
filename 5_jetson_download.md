# 5 Jetson download


### 1 web


download center:
https://developer.nvidia.com/zh-cn/embedded/downloads


JetPack:

https://developer.nvidia.com/embedded/jetpack-archive



=============================================================

https://www.cnblogs.com/qiyuexin/p/11266325.html

git submodule 删除及修改



kernel/nvgpu
kernel/nvhost
kernel/nvmap
kernel/display
hardware/nvidia/platform/tegra/common
hardware/nvidia/soc/t210
hardware/nvidia/platform/t210/common
hardware/nvidia/platform/t210/jetson
hardware/nvidia/soc/tegra
kernel/kernel-4-4
u-boot
tegra-pinmux-scripts


tom@tom-virtual-machine:~/ws_jetson/env_TX1/tg-tx1-kernel-build$ cat .gitmodules 
[submodule "kernel/nvgpu"]
	path = kernel/nvgpu
	url = git://nv-tegra.nvidia.com/linux-nvgpu.git
	branch = l4t/l4t-r28.2
[submodule "kernel/nvhost"]
	path = kernel/nvhost
	url = git://nv-tegra.nvidia.com/linux-nvhost.git
	branch = l4t/l4t-r28.2
[submodule "kernel/nvmap"]
	path = kernel/nvmap
	url = git://nv-tegra.nvidia.com/linux-nvmap.git
	branch = l4t/l4t-r28.2
[submodule "kernel/display"]
	path = kernel/display
	url = git://nv-tegra.nvidia.com/linux-display.git
	branch = l4t/l4t-r28.2
[submodule "hardware/nvidia/platform/tegra/common"]
	path = hardware/nvidia/platform/tegra/common
	url = git@github.com:Israel-TG-17/hardware-nvidia-platform-tegra-common-downstream.git
	branch = tg/master
[submodule "hardware/nvidia/soc/t210"]
	path = hardware/nvidia/soc/t210
	url = git@github.com:Israel-TG-17/hardware-nvidia-soc-t210-downstream.git
	branch = tg/master
[submodule "hardware/nvidia/platform/t210/common"]
	path = hardware/nvidia/platform/t210/common
	url = git@github.com:Israel-TG-17/hardware-nvidia-platform-t210-common-downstream.git
	branch = tg/master
[submodule "hardware/nvidia/platform/t210/jetson"]
	path = hardware/nvidia/platform/t210/jetson
	url = git@github.com:Israel-TG-17/hardware-nvidia-platform-t210-jetson-downstream.git
	branch = tg/master
[submodule "hardware/nvidia/soc/tegra"]
	path = hardware/nvidia/soc/tegra
	url = git@github.com:Israel-TG-17/hardware-nvidia-soc-tegra-downstream.git
	branch = tg/master
[submodule "kernel/kernel-4-4"]
	path = kernel/kernel-4-4
	url = git@github.com:Israel-TG-17/tx1-linux-4.4-downstream.git
	branch = tg/master
	shallow = true
[submodule "u-boot"]
	path = u-boot
	url = git@github.com:Israel-TG-17/u-boot-downstream.git
	branch = tg/master
[submodule "tegra-pinmux-scripts"]
	path = tegra-pinmux-scripts
	url = git@github.com:Israel-TG-17/tegra-pinmux-scripts-downstream.git
	branch = tg/master
tom@tom-virtual-machine:~/ws_jetson/env_TX1/tg-tx1-kernel-build$



















---
Jetson Guide:
https://developer.nvidia.com/embedded/learn/get-started-jetson-nano-devkit#write
