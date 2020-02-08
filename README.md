### freenas-plugin-index

#### This branch is for FreeNAS 11.3
- Check the Community Plugin page on your FreeNAS first
- Most of these can be installed without using the command line

#### Installing from the command line

### New plugins not available in the FreeNAS webui

**ESPHome**
```bash
iocage fetch -P esphome -g https://github.com/tprelog/freenas-plugin-index.git
```

### Available FreeNAS Community Plugins
- **Gogs**
- **Home Assistant Core**
- **Node-RED**
- **Mosquitto (MQTT Broker)**
- **TasmoAdmin**

---

- Installing from a different branch (For other options check the iocage docs)
```
iocage fetch -P PLUGIN_NAME -g https://github.com/tprelog/freenas-plugin-index.git --branch BRANCH --name NAME
```
