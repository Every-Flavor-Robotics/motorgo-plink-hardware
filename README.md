# MotorGo Plink
## The aim of this project is to make a 4 DC motor drive compatible with the motorgo ecosystem - specifically designed for beginner roboticists.  It should be the form factor of a pihat, but capable of operating entirely on it's own as well. Currently testing release version 1.0!
![plink](https://github.com/user-attachments/assets/7d676929-7b50-43c3-9a50-33d432836e92)

### Feature list:
- Esp32s3 with Wifi and BT connectivity
- Form factor of a PiHat (we do not currently have the EEPROM requirements of the PiHat Spec)
- DC barrel jack and on-board buck from 6-17V into 5.1V up to 6A  (enough to power pi4 and pi5)
- 9 dof IMU  (LSM6DSOTR-C accel and gyro  +  LIS3MDLTR mag)
- USB-C programming compatible with arduino IDE
- Qwiic port x2 for easy integration with sensors
- Full gpio breakout on 40Pin header + full RPi GPIO passthrough if using as a hat
- 4 bidirectional DC motor channels up to 2A each channel
- 4 Encoder ports for use with EncoderGo 5pin jst for close loop feedback on each motor

### Schematics: 
- Top level
![image](https://github.com/user-attachments/assets/46971f5e-88b7-499d-a4db-0fa14fc34dd8)

- Motor drivers
![image](https://github.com/user-attachments/assets/8e20d847-9494-4d3b-89d4-70819a153c33)

- IMU 
![image](https://github.com/user-attachments/assets/7b167ef6-7942-4b3c-a94c-fcc13daed4d6)

- Power system 
![image](https://github.com/user-attachments/assets/a7ccc587-862d-4dd4-a461-4bea1ef4754c)

- connectors 
![image](https://github.com/user-attachments/assets/af52febb-76ac-4a91-a71f-54a55d24eec4)

### Layout:
- Top - signals components and power
![image](https://github.com/user-attachments/assets/87813257-bdae-4176-9abd-03a49c26bd78)

- Inner 1 - GND (I left faint top layer to show ground relative to traces)
![image](https://github.com/user-attachments/assets/dbecf977-5f57-480d-889b-e9a645e3dd59)

- Inner 2 - GND and a tiny tiny power traces where needed
![image](https://github.com/user-attachments/assets/a202432c-91c7-4abe-baae-86d4832ffd88)

- Bottom - signals and power
![image](https://github.com/user-attachments/assets/bc55da6b-1892-4916-8866-5448f8465be3)

- Dimensions
![image](https://github.com/user-attachments/assets/22c7f30d-700c-4056-9f08-6dc1528d7d30)

- Full
![image](https://github.com/user-attachments/assets/08fe2d1f-9a51-48d9-94c5-0d79055b7677)
![image](https://github.com/user-attachments/assets/0174be1c-5cfc-44c0-b2fe-31ce48aebfa0)
![image](https://github.com/user-attachments/assets/288e9c9e-d7ad-4278-9922-6ebc89d9881d)

