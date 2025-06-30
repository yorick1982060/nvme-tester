# NVMe Tester

**NVMe Tester** is a tool designed to verify and stress-test NVMe SSDs on Ubuntu systems.  
> ⚠️ **Warning:** This tool may erase or damage data on the target SSD. **Use at your own risk.**

---

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

## 📂 Contents

The release currently includes **7 scripts** for NVMe device testing.

---

## 🚀 How to Use

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
