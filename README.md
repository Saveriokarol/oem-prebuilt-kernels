# Prebuilt Kernels Archive for OEM-specific devices

## About

This repository contains prebuilt Linux kernels for various OEM devices. The goal is to provide an organized collection of ready-to-use kernels for different manufacturers and models, making it easier for users to find and install a compatible kernel for their system.

## &#x20;Repository Structure

The directory structure follows this format:

```
/[vendor]/[model]/[kversion]/
```

### Example Structure:

```
/dell/vostro2520/6.1/
    ├── z/bz/Image (actual kernel file)
    ├── modules.cpio (cpio archive which contains a patched /lib for modules if they are built)
    ├── info.txt (kernel source links)
    ├── config (kernel configuration used for building)
```

&#x20;  &#x20;

## &#x20;How to Use

1. Navigate to the appropriate directory based on your **vendor** and **model**.

2. Download the prebuilt kernel file.

3. Follow the installation guide provided in the directory.

## Contributing

Contributions are welcome! To submit a new prebuilt kernel:

1. Fork this repository.

2. Add a new directory in the correct format (`/[vendor]/[model]/[kversion]/`).

3. Include the necessary files (`z/bz/Image`, `config`, `modules.cpio`, etc.).

## &#x20;Disclaimer

These kernels are provided as-is without any warranty. Use at your own risk. Ensure that the kernel is compatible with your system before installation.

***

Maintained by the community. Feel free to contribute and improve this archive!

