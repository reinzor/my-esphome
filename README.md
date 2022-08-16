# ESP home configuration

  ESPHome configurations files used in my home.

## Set-up

### Install dependencies

```
pip3 install --user esphome
```

### Setup `secrets` file

```bash
touch includes/secrets.yaml
vim includes/secrets.yaml
```

Copy paste the following:

```
wifi:
  ssid: "SSID"
  password: "PASSWORD"
```

Edit the `SSID` and `PASSWORD` for your wifi network.

## Flash / update a board

```
esphome <config.yaml> run
```
