# Ax64VM - VirGL OpenGL 3D Accelerated QEMU Wrapper for Termux Android

Ax64VM is a transformative wrapper that brings the arcane wonders of VirGL's OpenGL 3D acceleration to Termux Android. Embrace the power of accelerated 3D graphics within a mystical fusion of VirGL and QEMU.

## Overview
Enter the realm of Ax64VM, a mystical fusion of VirGL's 3D acceleration and QEMU's enigmatic embrace, crafted exclusively for Termux Android. With its intricate wrapper, Ax64VM beckons users to unlock the captivating powers of OpenGL and indulge in the mesmerizing world of accelerated 3D graphics.


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
   $ git clone https://github.com/Questandachievement7Developers/ax64vm
   ```
3. Navigate to the cloned repository
   ```shell
   $ cd ax64vm
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

## Background and Inspiration
The genesis of Ax64VM finds its roots in the inspiration drawn from the availability of iOS UTM—an ingenious creation that enables the utilization of Metal for virtio-ramfb-gl, thereby empowering iOS devices to harness the full potential of OpenGL acceleration. This remarkable capability left Android, and indeed any non-Apple Silicon ARM-based device, in a state of deprivation, languishing without OpenGL acceleration. It became apparent that Android, with its vast ecosystem of devices, was in dire need of a solution.

Motivated by this disparity, Ax64VM was conceived as a transformative wrapper, transcending the limitations imposed on Android systems. It aimed to bridge the gap and deliver OpenGL acceleration to the Android platform. The journey began with an exploration of the Snapdragon 888, a flagship Android SoC known for its prowess, only to discover that it, too, fell short in providing optimal performance.

As the development of Ax64VM unfolded, a deeper understanding emerged regarding the challenges faced by Android SoC CPUs. The limitations and disparities experienced on the Snapdragon 888 and similar chipsets revealed a need for a comprehensive solution that could empower Android devices to unleash the true potential of OpenGL acceleration.

With this newfound knowledge, Ax64VM emerged as a testament to the relentless pursuit of innovation and the desire to empower the Android ecosystem. By weaving together VirGL's 3D acceleration, QEMU's virtualization capabilities, and the mystic powers of OpenGL, Ax64VM aspires to uplift Android, ensuring that devices powered by non-Apple Silicon ARM CPUs can also experience the transformative magic of accelerated graphics.

In the enchanting realm of Ax64VM, Android is no longer left in the dust, but rather, it emerges as a platform capable of transcending limitations, embracing innovation, and empowering its users with the wondrous realms of OpenGL acceleration.
