# Project Title: Kernel Module for Reporting Elapsed Seconds

## Group Members:
- **Partik Dev**
- **Gurman Johal**

## Contributions:

### Partik Dev:
- Implemented the core functionality of the kernel module to calculate and report the elapsed time using `jiffies` and `HZ`.
- Handled the creation and removal of the `/proc/seconds` file.
- Wrote and refined the `proc_read` function to handle user requests for elapsed time data.
- Added comments and ensured code readability and documentation.

### Gurman Johal:
- Assisted with setting up and configuring the Linux environment and compiling the kernel module.
- Implemented the initialization and cleanup functions (`proc_init` and `proc_exit`).
- Helped test the module, including edge cases and various scenarios for the `/proc/seconds` file.
- Contributed to the overall documentation, including this `Readme`.
