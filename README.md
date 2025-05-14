# NITIN_0970
# Embedded Linux Security Modules & MACsec Integration

This repository showcases my work on embedded Linux systems, focusing on kernel hardening, MACsec integration, and automated unit testing. The development was carried out as part of my role as an Embedded Software Engineer, where I worked with Yocto Project, Linux kernel internals, and security modules to build secure, high-performance systems.

## 📌 Overview

- ✅ Developed and integrated **Kernel Hardening Modules** for enhanced OS security.
- ✅ Achieved **100% unit test coverage** for all kernel modules using automated test frameworks.
- ✅ Built secure embedded systems using the **Yocto Project** for custom Linux distributions.
- ✅ Worked on **MACsec (802.1AE)** implementation and unit testing.
- ✅ Gained deep experience in **Linux internals**, security, and performance optimization.

## 🧩 Key Components

### 🔐 Kernel Hardening Modules
- Implemented hardening features such as:
  - Stack protector
  - Kernel Address Space Layout Randomization (KASLR)
  - Restricting kernel module loading/unloading
  - Sysctl configuration hardening
  - Control Flow Integrity (CFI)

### 🧪 Unit Testing
- Designed and implemented **automated unit tests** for each module.
- Tools & Frameworks used:
  - `kselftest`
  - `kcov` for test coverage
  - Custom bash/Python test runners
- **100% test coverage** ensured for all modules.

### 🧬 MACsec (Media Access Control Security)
- Worked on configuring and validating MACsec functionality.
- Used **MKA Daemon (MKAD)** for key agreement protocol implementation.
- Setup included:
  - Secure communication between Linux systems
  - EAPOL-MKA frame handling
  - Verification of secure channel establishment

### 🛠 Yocto Project
- Created custom Linux builds for embedded hardware.
- Integrated kernel hardening configurations directly into the Yocto layers.
- Wrote and managed `.bb` recipes for custom modules.

## 💻 Technologies Used
- **Languages**: C, Shell Scripting, Python
- **Tools**: Yocto, Git, GCC, Kcov, Kselftest, QEMU, Wireshark
- **OS**: Embedded Linux, Ubuntu
- **Security Protocols**: MACsec, MKA

## 📂 Project Structure

```bash
.
├── kernel_modules/
│   ├── hardening_module_1/
│   ├── hardening_module_2/
├── macsec/
│   ├── mkad_setup/
│   ├── packet_capture/
├── tests/
│   ├── unit_tests/
│   ├── coverage_reports/
├── yocto/
│   ├── meta-custom-layer/
├── README.md
