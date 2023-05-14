# Ax64VM - VirGL OpenGL 3D Accelerated QEMU Wrapper for Termux Android

**⚠️ Warning: Ax64VM is currently in beta**

## Overview
Enter the realm of Ax64VM, a mystical fusion of VirGL's 3D acceleration and QEMU's enigmatic embrace, crafted exclusively for Termux Android. With its intricate wrapper, Ax64VM beckons users to unlock the captivating powers of OpenGL and indulge in the mesmerizing world of accelerated 3D graphics but in a non accelerated CPU slow processing manner.


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
   $ chmod +x ./ax64vm
   ```
5. Run the ax64vm.sh script:
**Warning: Ensure that no other VNC server is running on port 5900.**
   ```shell
   $ ./ax64vm
   ```
 6. Connect to the Ax64VM display using a VNC viewer with the address localhost:5900

## Background and Inspiration
The development of Ax64VM was inspired by the availability of iOS UTM, which allows the utilization of Metal for virtio-ramfb-gl, essentially enabling OpenGL usage on iOS devices. However, Android, along with other non-Apple Silicon ARM-based devices, has been left in the dust, lacking OpenGL acceleration. This led to the creation of Ax64VM, aiming to fill this void.

During the development process, I gained insights into the limitations of Android ARM SoC CPUs, particularly evident when testing on the Snapdragon 888. The Snapdragon 888 proved to be slower and more power-hungry compared to my old iPhone Xs, which inevitably affects the performance of Ax64VM. Nonetheless, driven by my curiosity and the desire to explore the possibilities, I couldn't resist diving into this endeavor.

## Issue Submission
If you encounter any issues or have any questions, please submit an issue on the GitHub repository with the following details:

- Subject: Briefly describe the issue you are facing
- Logs: Attach the ax64vm.log file located in the working directory
- Phone Model: Specify the model of your phone
- Android/ROM Model: Provide information about your Android version or custom ROM

Your feedback and bug reports are invaluable in improving Ax64VM and ensuring a seamless experience for all users.

## License
Ax64VM is licensed under the GPL-2.0 License. Feel free to explore, modify, and distribute the codebase in compliance with the terms and conditions of the GPL-2.0 License.

## Credits 
Ax64VM is the creation of visionary developers, weaving their spells into reality:

- Albert Starfield Wahyu Suryo Samudro (GitHub)
- Questandachievement (GitHub)

## License

Ax64VM is licensed under the GPL-2.0 License. Feel free to explore, modify, and distribute the codebase in compliance with the terms and conditions of the GPL-2.0 License.

---
```
**Note:** Yes, I'm aware that there might be an abundance of marketing-style language or a touch of medieval wording in this description. I'm just experimenting with different writing styles. If you have any questions or critiques, feel free to message me. Your feedback is valuable. -Albert
```
