# FormCodeTHPTTANHLINH
*Form code Thiết bị dự báo sớm cháy rừng và sạt lở đất.
center.ino : Để nạp cho bộ xử lí trung tâm (ESP32)
function_template_for_sensor.ino : để thêm thiết bị trong hàm loop() 
tremors_sensor.ino : code nạp cảm biến rung (ArduinoNano)
fire_forecast_sensor.ino : code nạp cảm biến cháy (ArduinoNano)
**********************************************************************
Tanh Linh HS - Lam Dong_VN
**********************************************************************
Lưu ý: 
1. Đây là code thiết lập lần đầu cho thiết bị, những lần sau đó chỉ cần cấp nguồn, kết nối Center với router WiFi 
theo đúng thiết lập trong biến ssid[] và pass[] là sử dụng như bình thường.
2. Trong Arduino IDE, cần tải thêm thư viện LoRa, Blynk và cài thêm ESP32 Arduino board manager mới có thể Verify và Update(nạp code).
**********************************************************************
Link video hướng dẫn (GoogleDrive) : https://drive.google.com/file/d/1FQCdZVUWYdPjaYtAYEwKmMPLhFtlp4NN/view?usp=drive_link
