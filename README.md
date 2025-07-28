# can-gauge
Electronic CAN-enabled gauge for vehicles.

# Design Requirements

## Mechanical requirements

- The gauge shall be sized to fit 52 mm standard automotive gauge pod mounting dimensions.

- The depth of the enclosure shall not exceed 60 mm to accommodate tight dashboards.

- All connectors shall be rear-facing for clean wiring integration.

## Electrical Requirements

- The gauge shall support an input voltage range of 8 – 16 VDC

- The gauge shall include reverse polarity protection.

- The gauge shall include surge proteciton up to 60V transients, and HBM-level ESD protection for automotive environments

## Display and Interface Requirements

- The gauge shall include a circular display of at least 45 mm diameter.

- The display shall be sunlight readable with at least 800 nits brightness.

- The user shall be able to configure display types: numeric, bar, dial, warning light, etc.

- Display update rate shall be at least 60 Hz for smooth animation

## Communication Requirements

- The gauge shall support CAN 2.0B at a bit rate from 125 kbps to 1 Mbps.

- The gauge shall support importing DBC files or equivalent for message decoding.

- The gauge shall support firmware updates and configuration via CAN or USB.

- The gauge shall include Bluetooth Low Energy (BLE) connectivity for configuration.

## Software Requirements

- The gauge shall support desktop and mobile configuration tools.

- Configuration settings shall be stored in non-volatile memory.

- The gauge shall boot and begin displaying data within 1 second of power-on.

## Enviornmental Requirements

- Operating temperature range: –40°C to +85°C.

- Storage temperature range: –55°C to +105°C.

- The housing shall be resistant to vibration up to 20 g RMS (motorsport-grade).

- The face, enclosure, and electrical connector shall be rated to at least IP65 (dust-tight and water-resistant).