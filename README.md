# CentOS LVM Setup

## Project Overview

This repository contains the steps and code used to complete a comprehensive lab focused on setting up LVM (Logical Volume Management) on CentOS. It includes the following tasks:

1. **Creating and Managing User Groups**
2. **Installing Necessary Packages**
3. **Setting Up Physical Volumes (PV)**
4. **Creating Volume Groups (VG)**
5. **Creating Logical Volumes (LV)**
6. **Formatting and Mounting Filesystems**
7. **Ensuring Persistence Across Reboots**
8. **Permission Management**

## Step-by-Step Guide

### 1. Create a new user group `dba_users`:
```bash
sudo groupadd dba_users
