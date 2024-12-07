# esphome-tesla-bms

![image](https://github.com/user-attachments/assets/6e497237-0f3c-424d-8fbb-cfb232529f40)


This code reads the Tesla battery BMS SOC data to esphome so far
All the values and names are from the tesla vehicle DBC files like this one https://github.com/onyx-m2/onyx-m2-dbc/blob/main/tesla_model3.dbc

https://github.com/cantools/cantools is great for generating the required decoding logic 
once installed you can run:
```
 cantools generate_c_source something.dbc
```

The code is currently running on the highlighted ESP32-S3 M5stack Atom S3 + Atomic CAN Base
![image](https://github.com/user-attachments/assets/54c83695-129e-4845-a635-828e6e4fcedd)


