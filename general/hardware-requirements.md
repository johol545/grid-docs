# Hardware requirements
Ombori Grid is very flexible in terms of hardware, however we have some minimum requirements for each hardware type. If you have any questions if certain hardware is supported in your specific case please contact us on [Slack](https://join.slack.com/t/slack-pgo5586/shared_invite/zt-s1ajca83-k8i1f2mqgCMD0vDfpCk4Bg).

Keep in mind all these specifications are minimum specifications, anything above would work as well.

## Intel
A wide variety of Intel CPU-based devices are supported by Ombori Grid and GridOS. When [adding the device](/general/adding-device/) just make sure to follow the Intel (NUC) installation guide.

Supported application types: Screen App, IoT App

**Minimum requirements**

- Intel Celeron Quad Core 1.5GHz
- 10GB disk space
- 4GB RAM

Example devices: Intel NUC, Intel Compute Stick, Surface Go, Surface Pro, and many more.

## Raspberry Pi
Raspberry Pi 4 is supported by Ombori Grid and GridOS.

Supported application types: Screen App, IoT App

**Minimum requirements**
- Raspberry Pi 4 4GB
- SD Card A2. Read Speed > 150MB/s. Write Speed > 60MB/s
- Heatsink case with fans

A heatsink is not strictly required, but recommended. Depending on what will be running on RPI, the hardware can potentially get hot.

# Installation Instructions
There are some devices which need special steps to configure during installation. Soon, these special steps will be included in our core releases.

## Elo i2 15"
Elo i2 devices require additional configuration for black screen issues.

```
cd ~
sudo git clone https://github.com/ombori/omb-elo-i2-15-fix
cd KMS-FixForBlackScreen
sudo bash fix_blackscreen.sh
```
