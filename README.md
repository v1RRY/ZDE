<h1 align="center">ZDE</h1>
<p align="center">Rework of EblanDE on Wayland, not X.Org!</p>
<hr>

**Akhtung! ZDE isn't recommended for use in a real work. This is made just for fun!**

# Installing

For now there is no packages in repositories (AUR, DEB, DNF), but you can install ZDE manually. First, you should clone the repository:

```shell
git clone https://github.com/ZDesktopEnvironment/ZDE
```

...then, you should install all of the dependencies:

```shell
pacman -S labwc python3 tk moka swaybg nwg-panel
```

...and copy ZDE to your system:

```shell
cd ZDE
cp -rfv tree/* /
```
