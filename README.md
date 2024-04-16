# ระบบควบคุม LED และเก็บข้อมูลอุณหภูมิและความชื้นลงในไฟล์ json ผ่าน MQTT

## Json Server Command
<code>json-server --watch data.json --host <input_ip> --port <input_port></code>

## โครงสร้างข้อมูล
```json
{
  "dht11": [
    {
      "humidity": 58,
      "temperature": 24.39999962,
      "ip": "192.168.43.76",
      "id": 1
    },
    {
      "humidity": 48,
      "temperature": 24.89999962,
      "ip": "192.168.43.76",
      "id": 2
    }
  ]
}
```

## Click image to Youtube video
[![Screenshot 2024-04-16 131332](https://github.com/TOEYJIRAKID/MQTT-DHT-LED-IOT/assets/167008371/923ef488-634b-44c9-b63f-0ca2a5dec4a0)](https://youtu.be/807F1Wtq8c8?si=03tMChkQ75pBkBoH) 
