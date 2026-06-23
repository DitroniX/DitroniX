# DitroniX Mains Power Polyphase IoT Energy Monitor Comparisons

**Supporting STEM Electronic Internet of Things & Home Automation Technology for Smart Energy Monitoring**

**Home | Education | Commercial | Industrial | Farming & Agriculture | Solar | Wind**

Any questions or queries, please [contact](https://ditronix.net/contact/) me.

## Prelude

All of the DitroniX Mains Energy Monitor boards integrate the Microchip [ATM90E32AS](https://github.com/DitroniX/IPEM-SIX-ESP32C5-ATM90E32-IoT-Mains-Power-Energy-Monitor/wiki/ATM90E32-Block-Diagram) or [ATM90E36A](https://github.com/DitroniX/IPEM-Plus-ESP32-C5-LoRa-LoRaWAN-IoT-Mains-Power-Energy-Monitor/wiki/ATM90E36-Block-Diagram) to provide Accurate Polyphase Mains Monitoring and 0.1% active energy accuracy.

Importantly all boards are designed to be low voltage only, as safety is important, and absolute minimum, to no, calibration required. Example code is provided in each repository and also in the [Home Assistant](https://github.com/DitroniX/Home-Assistant-Dev) area.

### Supported

| ESPHome <br>Home Assistant | Espressif<br> ESP-IDF | Arduino | Platform IO | MQTT | Domoticz openHAB<br> Tasmota Etc. | Raspberry Pi<br>and other Flavours|
|-------------|-------------|-------------|-------------|-------------|-------------|-------------|
| ✅      | ✅      | ✅      | ✅          | ✅   | ✅           | ✅           |

### Phases

| Single Phase | Single Phase<br>Multi Channel | Dual Phase | Split Phase | Three Phase<br>Delta Δ (3P3W) | Three Phase<br>Star Y (3P4W) |
|--------------|----------------------------|------------|-------------|----------------------------|---------------------------|
| ✅           | ✅                         | ✅         | ✅          | ✅                         | ✅                        |

- Delta (Δ), 3-phase 3-wire, forms a closed loop without a neutral (3 x Current Inputs).
- Star (Y), 3-phase 4-wire, creates a central neutral point (4 x Current Inputs).   

### Suitable for Applications

🏠 Home |🏭 Industrial |⚡ EV |☀ Solar |🌬 Wind |🚜 Agriculture |🎓 Education |🔋 Battery

### Quick Recommendations
- **Best for most Homes/Small Businesses** — **IPEM SIX** (Excellent multi-circuit monitoring)
- **Ethernet and Homes/Small Businesses** — **EPEM** (Uses shared SPI Port)
- **Remote / Off-Grid** — **IPEM NB-IoT** (LPWA/NB-IoT/CAT-M/GNSS) **IPEM Plus** (LoRa/LoRaWAN/FSK)
- **AI / Advanced Processing and Ethernet** — **IPEM S3-AI** (Uses dedicated SPI Port)
- **Raspberry Pi users** — **IPEM PiHat** (Stackable)


## Summary of boards:

### **[IPEM S3-AI](https://github.com/DitroniX/IPEM-S3-AI-ESP32-S3-IoT-Ethernet-Mains-Power-Energy-Monitor)** (August 2026)
New to the IPEM family, this board offers an Espressif ESP32-S3 with ATM90E36A, which is also ideal for AI/Advanced processing integration in analysing detailed Mains Power Energy. Ethernet is also included (using dedicated SPI port). The power of the S3 enables faster processing and calculations. RS485/Modbus/DMX interface is included. With Home Assistant / ESPHome Support. DIN Rail Option.

| Wi-Fi 2.4GHz | Wi-Fi 5GHz | ETH | BLE | Thread | Zigbee | LoRa | NB-IoT | RS485 |
|--------------|------------|-----|-----|--------|--------|------|--------|-------|
| ✅           | ✅         | ✅  | ✅  | ❌     | ❌     | ❌   | ❌     | ✅    |

### **[IPEM SIX](https://github.com/DitroniX/IPEM-SIX-ESP32C5-ATM90E32-IoT-Mains-Power-Energy-Monitor)** (New)
This is a true SIX channel Dual ATM90E32AS, Espressif ESP32-C5 based Mains Power Energy Monitor. With Home Assistant / ESPHome Support. Whilst this is a professional board, it is aimed at Home and Small Business/Industry users who would like to accurately measure more circuits on 1, 2 or 3-phases (excluding 3-Phase Neutral). RS485/Modbus/DMX interface is included. DIN Rail Option.

| Wi-Fi 2.4GHz | Wi-Fi 5GHz | ETH | BLE | Thread | Zigbee | LoRa | NB-IoT | RS485 |
|--------------|------------|-----|-----|--------|--------|------|--------|-------|
| ✅           | ✅         | ❌  | ✅  | ✅     | ✅     | ❌   | ❌     | ✅    |

### **[IPEM NB-IoT](https://github.com/DitroniX/IPEM-NBIoT-ESP32C5-ATM90E36-SIM7070G-GPRS-IoT-Mains-Power-Energy-Monitor)** (New)
Incorporating the SIM7070G, this Espressif ESP32-C5, with an ATM90E36A, Mains Power Energy provides onboard Cat-M, NB-IoT, and 2G/EDGE networking, with GPRS/GNSS. This is ideal for remote monitoring, using the cellular network. RS485/Modbus/DMX interface is included. DIN Rail Option.

| Wi-Fi 2.4GHz | Wi-Fi 5GHz | ETH | BLE | Thread | Zigbee | LoRa | NB-IoT | RS485 |
|--------------|------------|-----|-----|--------|--------|------|--------|-------|
| ✅           | ✅         | ❌  | ✅  | ✅     | ✅     | ❌   | ✅     | ✅    |

### **[IPEM Plus](https://github.com/DitroniX/IPEM-Plus-ESP32-C5-LoRa-LoRaWAN-IoT-Mains-Power-Energy-Monitor)** (New)
Building on our reliable Espressif ESP32-C6 Mains Power Energy monitors, the on-board popular SX1262 provides LoRa, LoRaWAN and FSK support. This allows remote power monitoring. RS485/Modbus/DMX interface is included. DIN Rail Option.

| Wi-Fi 2.4GHz | Wi-Fi 5GHz | ETH | BLE | Thread | Zigbee | LoRa | NB-IoT | RS485 |
|--------------|------------|-----|-----|--------|--------|------|--------|-------|
| ✅           | ❌         | ❌  | ✅  | ✅     | ✅     | ✅   | ❌     | ✅    |

### **[EPEM](https://github.com/DitroniX/EPEM-Ethernet-Power-Energy-Monitor)** 
This Espressif ESP32-C6 Mains Energy Monitor includes Ethernet (shared SPI port). It is available with either ATM90E32AS or ATM90E36A. With Home Assistant / ESPHome Support. RS485/Modbus/DMX interface is included.

| Wi-Fi 2.4GHz | Wi-Fi 5GHz | ETH | BLE | Thread | Zigbee | LoRa | NB-IoT | RS485 |
|--------------|------------|-----|-----|--------|--------|------|--------|-------|
| ✅           | ❌         | ✅  | ✅  | ✅     | ✅     | ❌   | ❌     | ✅    |

### **[IPEM PiHat](https://github.com/DitroniX/IPEM-PiHat-IoT-Power-Energy-Monitor)**
Building on the IPEM Mains Power Energy Monitor theme, this is aimed at Raspberry Pi users who would like to integrate monitoring on the Pi, using the ATM90E36A. It comes in two flavours, IPEM PiHat and IPEM PiHat Lite. The board can also be [stacked](https://github.com/DitroniX/IPEM-PiHat-IoT-Power-Energy-Monitor/wiki/IPEM-PiHat-Stacking) to provide many inputs.

| Wi-Fi 2.4GHz | Wi-Fi 5GHz | ETH | BLE | Thread | Zigbee | LoRa | NB-IoT | RS485 |
|--------------|------------|-----|-----|--------|--------|------|--------|-------|
| ✅ Pi        | ✅ Pi      | ✅ Pi| ✅ Pi| ✅ Pi  | ✅ Pi  | ✅ Pi| ✅ Pi  | ✅ Pi |

## Detailed Feature Comparison Chart

![DitroniX Mains Power IoT Energy Monitor Comparison](https://github.com/DitroniX/DitroniX/blob/main/Files/DitroniX%20Mains%20Power%20IoT%20Energy%20Monitor%20Comparison.jpg)

## PDF of Detailed Feature Comparison Chart
[Ditronix Mains Power IoT Energy Monitor Comparison PDF](https://github.com/DitroniX/DitroniX/blob/main/Files/Ditronix%20Mains%20Power%20IoT%20Energy%20Monitor%20Comparison.pdf)


