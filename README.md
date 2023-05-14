# Ax64VM - VirGL OpenGL 3D Accelerated QEMU Wrapper for Termux Android

Ax64VM is a transformative wrapper that brings the arcane wonders of VirGL's OpenGL 3D acceleration to Termux Android. Embrace the power of accelerated 3D graphics within a mystical fusion of VirGL and QEMU.

## Key Features

- **VirGL Wrapper:** Seamlessly integrate OpenGL-based 3D acceleration within Termux using Ax64VM's VirGL wrapper.
- **OpenGL 3D Acceleration:** Experience enhanced performance for running 3D applications and games with the power of OpenGL.
- **QEMU Integration:** Enjoy seamless integration with Termux through QEMU's virtualization capabilities.

## Default Configuration

Ax64VM provides a default configuration with a 32GB qcow2 image and automatically downloads the performance-optimized Alpine ISO image.

## Installation
1. Install the `git` package in Termux:

   ```shell
   $ pkg install git
   ```
2. Clone the Ax64VM repository
   ```shell
   $ git clone https://github.com/albertstarfield/Ax64VM.git
   ```
3. Navigate to the cloned repository
   ```shell
   $ cd Ax64VM
   ```
4. Grant executable permissions to the ax64vm.sh script
   ```shell
   $ chmod +x ./ax64vm.sh
   ```
5. Run the ax64vm.sh script:
**Warning: Ensure that no other VNC server is running on port 5900.**
   ```shell
   $ ./ax64vm.sh
   ```
 6. Connect to the Ax64VM display using a VNC viewer with the address localhost:5900
