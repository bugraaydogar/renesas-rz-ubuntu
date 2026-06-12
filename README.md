# Ubuntu images for Renesas RZ
Image and gadget definitions for Ubuntu on Renesas RZ boards

## Install dependencies

```
sudo apt update
sudo apt install git snapd qemu-user-static ubuntu-dev-tools
sudo snap install --classic ubuntu-image
```

## Build image

```
sudo ubuntu-image --sector-size=4096 classic server-image.yaml
```
or
```
sudo ubuntu-image --sector-size=4096 classic desktop-image.yaml
```
