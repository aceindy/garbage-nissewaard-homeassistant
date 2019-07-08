# Garbage collection sensor for Nissewaar for Home Assistant

in your configuration.yaml you'll need:

```yaml
sensor:
  - platform: nissewaard
    postcode: 0000AA
    housenumber: 1
    resources:
      - today
      - tomorrow
      - grey
      - green
      - paper
      - packages
```

It will create sensors for the next few future calendar events, called:

* sensor.nissewaard_groente_fruit_en_tuinafval
* sensor.nissewaard_papier_en_karton
* sensor.nissewaard_pmd
* sensor.nissewaard_restafval

and extra sensors:
* sensor.nissewaard_vandaag
* sensor.nissewaard_morgen
