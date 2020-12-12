# xiaomi_aqara
Gateway Xiaomi 1 min retrigger

Works with mijia and aqara motion sensors paired with Xiaomi's gateway. 

Just copy everything to the ”custom_component/xiaomi_aqara/” folder and restart HA.



With this change, the motion sensors will:
  - detect movement
  - staying "on" for 12 seconds
  - after another more 50 seconds, it will detect movement again.
  {62 seconds between detections}

If you change their hardware:
(https://community.smartthings.com/t/making-xiaomi-motion-sensor-a-super-motion-sensor/139806)
  - detect movement
  - staying "on" for 12 seconds
  - after another more 3 seconds, it will detect movement again.


With the original component it takes more than 2 minutes and 30 seconds between detections.
