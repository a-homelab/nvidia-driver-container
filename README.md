# nvidia-driver-container
Patch for upstream NVIDIA driver containers

```bash
$ git diff --no-index tmp/nvidia-driver.source tmp/nvidia-driver.patched > nvidia-driver.patch
```

```bash
$ patch -p1 tmp/nvidia-driver.source nvidia-driver.patch
```
