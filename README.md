# ESP32 OTA firmware

Binary: `nb_iot.bin` (ESP-IDF application image for ESP32-C3).

Direct download URL:

`https://raw.githubusercontent.com/Ruytung1997/downbin/main/nb_iot.bin`

Use this oneM2M Commander command to trigger OTA on the ESP32:

`{"Command":"HTTPOTA:https://raw.githubusercontent.com/Ruytung1997/downbin/main/nb_iot.bin"}`

The BC660K fetches this binary over HTTP(S); the image is installed to the inactive ESP32 OTA partition. This file does not update the BC660K modem firmware.
