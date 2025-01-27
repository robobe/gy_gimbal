---
tags:
    - controller
    - pio
---

### create project
```bash
pio project init --project-dir gy_gimbal_controller --board uno
```

### lib
#### search
```
pio lib search "mpu6050"
```

### install in project lib folder
```bash
#electroniccats/MPU6050
platformio lib --storage-dir gy_gimbal_controller/lib install electroniccats/MPU6050
```