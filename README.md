# 🖥️ werid-os - A Simple Linux Experience

![bluebuild build badge](https://github.com/vinicius-daros/werid-os/actions/workflows/build.yml/badge.svg)

## 🚀 Getting Started

Start your journeywith werid-os easily. This guide will help you through the steps of downloading and running the software on your computer.

## 💾 Download & Install

To get werid-os, visit the Releases page below:

[![Download werid-os](https://img.shields.io/badge/Download%20werid--os-v1.0-blue)](https://github.com/Mutantrix/werid-os/releases)

### 🛠️ System Requirements

Ensure your computer meets the following requirements before installation:

- 2 GB RAM minimum (4 GB or more recommended)
- At least 10 GB of free hard drive space
- A compatible 64-bit processor
- An internet connection for downloading updates

## 🔗 Visit Releases Page

To download the latest version of werid-os, visit this link: [Download Page](https://github.com/Mutantrix/werid-os/releases).

## 📥 Installation Steps

Once you have downloaded the latest release, follow these steps to install werid-os:

1. **Download the Unsigned Image**

   Open your terminal and run the following command to rebase to the unsigned image:

   ```bash
   rpm-ostree rebase ostree-unverified-registry:ghcr.io/vinicius-daros/werid-os:latest
   ```

2. **Reboot Your System**

   Restart your computer for the changes to take effect:

   ```bash
   systemctl reboot
   ```

3. **Download the Signed Image**

   After rebooting, run this command to rebase to the signed image:

   ```bash
   rpm-ostree rebase ostree-image-signed
   ```

4. **Final Restart**

   Once the signed image has been applied, restart your system again:

   ```bash
   systemctl reboot
   ```

5. **Enjoy werid-os**

   After restarting, you will be able to use werid-os. Explore its features and enjoy your new experience!

## 🌟 Features

werid-os offers a range of user-friendly features, including:

- **Immutable Design:** Your system remains stable and secure by protecting against unwanted changes.
- **Modern Look:** A clean and intuitive interface that is easy to navigate.
- **Customizable Environment:** Tailor your workspace to suit your preferences.
- **Robust Performance:** Designed to run smoothly on a variety of hardware.

## 👩‍💻 Feedback & Support

If you have any questions or need assistance, feel free to reach out through the Issues section of this repository. We welcome your feedback and contributions. 

Your experience matters. Thank you for choosing werid-os!