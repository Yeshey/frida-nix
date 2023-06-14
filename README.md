# frida-nix

Big thanks to the authors of the [Original repo](https://github.com/itstarsun/frida-nix)

The only difference from this to the original repo is the change of the input packages to be from the 23.05 channel instead of unstable so it can be used in [my nixOS module](https://github.com/Yeshey/nixos-nvidia-vgpu_nixOS22.11).

```
$ nix profile install github:itstarsun/frida-nix
$ frida --version
16.0.19
```
