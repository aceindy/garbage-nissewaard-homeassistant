# Gemeente Nissewaard

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
