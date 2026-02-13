# Azure-Disk-Cost-Management
This script will:

1. **Detect VMs using Premium SSD (OS + Data disks)**

2. **Asks Admin: Convert to Standard SSD (StandardSSD_LRS)?** (yes/no)

3. **If yes:**

- Stops VM

- Deallocates VM

- Updates OS disk

- Updates Data disks (if any)

- Starts VM

- Displays final disk types

4. **If no → Skip VM**
