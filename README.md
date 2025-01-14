# DSS-Research-Paper-work
Man-In-The-Middle-Attack Mitigation In Internet of Medical Things - IEEE Research Paper

# Abstract
The Internet of Medical Things are suscepti
ble to Man-in-the-Middle (MitM) attack, which can identify
 healthcare emergency of monitored patients and replay
 normal physiological data to prevent the system from rais
ing an alarm. In this article, we propose a framework to pre
vent a MitM from disrupting the operations and prohibiting
 the raise of alarms by the remote healthcare monitoring
 system. To reduce energy consumption for normal data
 transmission, and preserve the privacy of health data, our
 framework transmits a smaller size signature derived from
 acquired data with message authentication code, where the
 key is derived from received signal strength indication. Our
 experimental results for emergency detection show that our
 approach can achieve a high detection accuracy with a low
 false alarm rate of 3%


 ![image](https://github.com/user-attachments/assets/e8c517a6-b7f1-4a14-bbd5-c990a1097283)

## Components of proposed framework

![image](https://github.com/user-attachments/assets/69368b08-522e-4329-bd93-175ff49421ad)


## Alert Generation Conditions:
### If both RSSI and LSH-Min Hash indicate an anomaly:
Trigger a high-priority alert indicating a strong likelihood of a genuine abnormality or security breach.
### If only one method detects an issue (RSSI fluctuates but LSH-Min Hash is normal):
Trigger a low-priority alert, allowing the monitoring system to log but not react with full intervention.
### If both methods are normal: 
No alert, as the data is considered consistent and authenticated.

![image](https://github.com/user-attachments/assets/e6f71e9b-3294-4b14-bc18-89812178c508)

