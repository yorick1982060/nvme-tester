## NVMe Tester
**NVMe Tester** is a tool designed to verify and stress-test NVMe SSDs on Ubuntu systems.  
> ⚠️ **Warning:** This tool may erase or damage data on the target SSD. **Use at your own risk.**


## NVMe Tester Glance
<img width="749" height="908" alt="image" src="https://github.com/user-attachments/assets/9061655f-b86d-4f42-ab85-1c7d12722a33" />

## Running Status Glance
<img width="895" height="793" alt="image" src="https://github.com/user-attachments/assets/3c7139ad-d850-4d67-b34d-3db507c6c1c1" />
<img width="887" height="497" alt="image" src="https://github.com/user-attachments/assets/88f64ff0-f65f-4955-b569-7597fe403e17" />

## Html Report Glance
<img width="909" height="663" alt="image" src="https://github.com/user-attachments/assets/f3d21244-853f-449b-bdb3-d4e719cfd8ab" />
<img width="912" height="523" alt="image" src="https://github.com/user-attachments/assets/216e8c4c-7bb4-474a-9466-be00f4f873b7" />
<img width="907" height="584" alt="image" src="https://github.com/user-attachments/assets/d4e8c6a1-127f-44c5-9f45-b2adb17833c8" />




## ⚙️ Requirements

- Ubuntu (64-bit)
- Intel CPU
- Minimum 4GB RAM
- An NVMe SSD installed in your PC (must **not** be the boot drive)

---

## ⚠️ Important Warnings

1. **This tool may destroy data** on the NVMe SSD being tested. If you are unsure of what you're doing, **do not use this tool**.
2. **Never run NVMe Tester on your boot drive.**
3. The author is **not responsible** for any damage or data loss caused by this application.

---

## Contents

The release currently includes **7 scripts** for NVMe device testing.

---

## How to Use

1. **Extract the package**  
   ```bash
   tar -xvf nvme-tester-v1.0-amd64.tar.gz
   ```

2. **Navigate to the directory and list available NVMe devices**  
   ```bash
   cd ./nvmet
   ./nvmet --list-dev
   ```

3. **Select a device to test**  
   Use the device address from the list. For example:  
   ```bash
   sudo ./nvmet 0000:01:00.0
   ```

4. **Get more options**  
   ```bash
   ./nvmet --help
   ```
