# Gemeente Nissewaard garbage collection in Home Assistant

based on https://github.com/vloris/home-assistant/blob/master/custom_components/sensor/twentemilieu.py

Gemeente Nissewaard sensor for garbage collection for Home Assistant


```
sensor:
  - platform: nissewaard
    postcode: 0000XB
    housenumber: 1
    resources:
      - today
      - tomorrow
      - grey
      - green
      - paper
      - packages
```
<a href="https://www.buymeacoffee.com/IWZoirH6k" target="_blank"><img src="https://bmc-cdn.nyc3.digitaloceanspaces.com/BMC-button-images/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: auto !important;width: auto !important;" ></a>
