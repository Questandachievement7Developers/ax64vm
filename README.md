# Ax64VM - VirGL OpenGL 3D Accelerated QEMU Wrapper for Termux Android

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

With this newfound knowledge, Ax64VM emerged as a testament to the relentless pursuit of innovation and the desire to empower the Android ecosystem. By weaving together VirGL's 3D acceleration, QEMU's virtualization capabilities, and the mystic powers of OpenGL, Ax64VM aspires to uplift Android, ensuring that devices powered by non-Apple Silicon ARM CPUs can also experience the magic of accelerated graphics.

## Contributing
Unleash your arcane potential and contribute to the evolution of Ax64VM. Delve into the sacred guidelines outlined in CONTRIBUTING.md, where you may reveal bug reports, unveil new features, or conjure mesmerizing pull requests.

## License
Ax64VM is licensed under the GPL-2.0 License. Feel free to explore, modify, and distribute the codebase in compliance with the terms and conditions of the GPL-2.0 License.

## Credits 
Ax64VM is the creation of visionary developers, weaving their spells into reality:

- Albert Starfield Wahyu Suryo Samudro (GitHub)
- Questandachievement (GitHub)

1. Ensure that you have the `git` package installed in Termux by executing the following command:

   ```shell
   $ pkg install git
   ```

2. Clone the Ax64VM GitHub repository by running the following command:

   ```shell
   $ git clone https://github.com/albertstarfield/Ax64VM.git
   ```

3. Navigate to the cloned repository by executing the following command:

   ```shell
   $ cd Ax64VM
   ```

4. Grant executable permissions to the `ax64vm.sh` script:

   ```shell
   $ chmod +x ./ax64vm.sh
   ```

5. Run the `ax64vm.sh` script to initiate the Ax64VM environment:

   **Warning: Ensure that no other VNC server is running on port 5900.**

   ```shell
   $ ./ax64vm.sh
   ```

6. Connect to the Ax64VM display using a VNC viewer with the address `localhost:5900`.

Unleash the captivating power of Ax64VM and explore the realms of accelerated 3D graphics within Termux Android. Let your imagination soar as you dive into a world crafted with VirGL's OpenGL acceleration and QEMU's mystical integration.

## License

Ax64VM is licensed under the GPL-2.0 License. Feel free to explore, modify, and distribute the codebase in compliance with the terms and conditions of the GPL-2.0 License.

---

**Note:** Yes, I'm aware that there might be an abundance of marketing-style language or a touch of medieval wording in this description. I'm just experimenting with different writing styles. If you have any questions or critiques, feel free to message me. Your feedback is valuable. -Albert
```
