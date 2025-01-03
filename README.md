# m5stack-demos
M5Stack unit, face &amp; atom demos

# M5Stack Faces (with M5Stack BASIC)
* [Faces Fingerprint](faces_finger_demo.m5f)
* [Faces Joystick](faces_joystick_demo.m5f) Works both of BASIC & Fire.

# HATs (with M5StickC Plus 1.1)
* [HAT YUN](stickc_hat_yun_demo.m5f)
* [ToF](faces_finger_demo.m5f)

# Atomic Base (with M5Atom Lite)
* [Motion](atom_motion_demo.m5f)
* [Scale Kit + DigiClock + PortABC](atom_lite_scale_kit_demo.m5f) 0~200kg, PortA: DigiClock, PortB: Scale Kit

# Atomic Base (with M5Atom Matrix)
* [GPS](atom_matrix_gps_demo.m5f)
* [GPS 115200bps](atom_matrix_gps_115200bps_demo.m5f) ※Change Baudrate setting by [u-center](https://www.u-blox.com/en/product/u-center) software. [u-center 設定方法日本語解説](https://intellectualcuriosity.hatenablog.com/entry/2020/07/01/041715)

# UNITs (with M5AtomU)
  Can be run in old UiFlow Desktop IDE
* [DigiClock](atomu_digiclock_countup_demo.m5f)
* [DigiClock + RTC](atomu_digiclock_rtc_demo.m5f)
* [DigiClock × 2 + RTC](atomu_2digiclock_rtc_demo.m5f) DigiClock 1: i2c 0x30, DigiClock 2: i2c 0x31
* [DigiClock × 6 + RTC](atomu_6digiclock_rtc_demo.m5f) DigiClock 1\~6: i2c 0x30\~0x35
* [DigiClock × 6 + RTC + NTP](atomu_6digiclock_rtc_ntp_demo.m5f.m5f) DigiClock 1\~6: i2c 0x30\~0x35 Sync with NTP every 1 hour (00:00).

# UNITs (with M5Stack Fire)
* [HALL](hall_unit_demo.m5f)
* [GPS](m5fire_unit_gps_demo.m5f)

# UNITs (with M5Stack BASIC)
* [DigiClock + RTC + NTP](digiclock_rtc_sync_ntp_demo.m5f) Sync RTC UNIT with NTP
* [Camera DIY KIT](m5core_unitcam_diy_kit_porta_demo.m5f)

# Third Party
* Atom Lite + [Door Sensor](atom_iot_door_sensor_GPIO33_demo.m5f) (GPIO 33) [SYNTEX SPS-320](https://akizukidenshi.com/catalog/g/g113371/)

# UiFLow Custom Block
* [MCU Info](MCUinfo.m5b)
* [RTC to DigiClock](RTC_to_DigiClock.m5b)
