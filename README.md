# BLE (ble)
Bluetooth Low Energy (BLE), also known as Bluetooth Smart, is a wireless personal area network technology designed and marketed by the Bluetooth Special Interest Group (Bluetooth SIG). Aimed at IoT and embedded applications, BLE provides reduced power consumption while maintaining similar communication range to classic Bluetooth. The specification is managed by the Bluetooth SIG and covers the full protocol stack including the Generic Attribute Profile (GATT), Generic Access Profile (GAP), and the various service and characteristic specifications used for device interoperability.

**URL:** [https://www.bluetooth.com](https://www.bluetooth.com)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - BLE, Bluetooth, Embedded, IoT, Protocols, Standards, Wireless

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-04-21

## APIs

### Bluetooth Core Specification
The Bluetooth Core Specification defines the complete Bluetooth wireless communication protocol stack including BLE (LE) and Classic Bluetooth. The current stable version is Bluetooth 6.0. The specification covers the Physical Layer, Link Layer, HCI, L2CAP, SM, GAP, and GATT layers, as well as LE Audio, Isochronous Channels, and Direction Finding extensions.

**Human URL:** [https://www.bluetooth.com/specifications/specs/core60/](https://www.bluetooth.com/specifications/specs/core60/)

#### Tags:

 - BLE, Bluetooth, Core Specification, Protocols, Standards

#### Properties

- [Documentation](https://www.bluetooth.com/specifications/specs/)
- [Specification](https://www.bluetooth.com/specifications/specs/core60/)
- [JSON Schema - GATT Service](json-schema/ble-gatt-service-schema.json)
- [JSON Schema - Advertising Packet](json-schema/ble-advertising-packet-schema.json)
- [JSON-LD Context](json-ld/ble-context.jsonld)
- [Example - Heart Rate Service](examples/ble-heart-rate-service-example.json)
- [Example - Advertising Packet](examples/ble-advertising-packet-example.json)

### GATT and Assigned Numbers
The Generic Attribute Profile (GATT) defines the framework for data transfer between Bluetooth LE devices. The Bluetooth SIG maintains assigned numbers for services, characteristics, and descriptors that enable interoperable implementations.

**Human URL:** [https://www.bluetooth.com/specifications/assigned-numbers/](https://www.bluetooth.com/specifications/assigned-numbers/)

#### Tags:

 - BLE, GATT, IoT, Profiles, Standards

#### Properties

- [Documentation](https://www.bluetooth.com/specifications/assigned-numbers/)
- [Specification](https://www.bluetooth.com/specifications/assigned-numbers/)

### Bluetooth Mesh Networking
Bluetooth Mesh enables many-to-many device communications and is particularly suited for IoT applications that require large-scale device networks, including building automation, industrial IoT, and smart city infrastructure.

**Human URL:** [https://www.bluetooth.com/specifications/specs/mesh-profile/](https://www.bluetooth.com/specifications/specs/mesh-profile/)

#### Tags:

 - BLE, IoT, Mesh, Networking, Standards

#### Properties

- [Documentation](https://www.bluetooth.com/specifications/specs/mesh-profile/)
- [Specification](https://www.bluetooth.com/specifications/specs/mesh-profile/)

## Common Properties

- [Website](https://www.bluetooth.com/)
- [Documentation](https://www.bluetooth.com/develop-with-bluetooth/)
- [Specification](https://www.bluetooth.com/specifications/specs/)
- [Training](https://www.bluetooth.com/develop-with-bluetooth/training/)
- [Community](https://www.bluetooth.com/develop-with-bluetooth/)
- [Developer Tools and SDKs](https://www.bluetooth.com/develop-with-bluetooth/developer-resources/)
- [Conformance and Qualification](https://www.bluetooth.com/develop-with-bluetooth/qualification-listing/)
- [Spectral Rules](rules/ble-spectral-rules.yml)
- [Naftiko Capability](capabilities/ble-gatt-capability.yaml)
- [Vocabulary](vocabulary/ble-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| Low Energy Protocol Stack | BLE defines a complete protocol stack from Physical Layer through Application, enabling ultra-low-power wireless communication for IoT and wearable devices. |
| Generic Attribute Profile (GATT) | GATT defines a client/server model for data exchange using services and characteristics, enabling standardized device interoperability across vendors. |
| Generic Access Profile (GAP) | GAP controls connections and advertising in BLE, defining how devices discover each other and establish connections. |
| Advertising and Scanning | BLE advertising allows devices to broadcast data without requiring a connection, enabling beacons, proximity sensing, and asset tracking. |
| LE Audio | Bluetooth 5.2+ LE Audio introduces LC3 codec, Auracast broadcast audio, and hearing aid profiles for next-generation wireless audio applications. |
| Direction Finding | Bluetooth 5.1+ Direction Finding supports Angle of Arrival (AoA) and Angle of Departure (AoD) for indoor positioning and real-time location. |
| Bluetooth Mesh | The Bluetooth Mesh specification enables many-to-many communications for large-scale IoT deployments in buildings, industry, and infrastructure. |

## Use Cases

| Name | Description |
|------|-------------|
| Wearable Health Devices | BLE powers fitness trackers, smartwatches, heart rate monitors, and medical wearables using standardized GATT health profiles. |
| Proximity Beacons | BLE beacons broadcast advertising packets for proximity detection, indoor positioning, and contextual notifications in retail and logistics. |
| Smart Home Automation | BLE Mesh enables smart lighting, HVAC control, and security systems in residential and commercial building automation. |
| Industrial IoT | BLE provides wireless sensor connectivity for industrial monitoring, predictive maintenance, and asset tracking applications. |
| Healthcare Monitoring | BLE medical devices including glucose meters, blood pressure monitors, and pulse oximeters use standardized health profiles for mobile integration. |

## Integrations

| Name | Description |
|------|-------------|
| Apple Core Bluetooth | iOS and macOS Core Bluetooth framework provides native BLE central and peripheral role implementation for Apple platform apps. |
| Android Bluetooth API | Android Bluetooth API provides BLE central and peripheral support for Android application development. |
| Zephyr RTOS | The Zephyr Project includes a full BLE stack (Zephyr BT) for embedded and IoT firmware development. |
| NRF Connect SDK | Nordic Semiconductor's nRF Connect SDK provides BLE and Bluetooth mesh implementation for nRF52 and nRF53 series SoCs. |
| Web Bluetooth API | The W3C Web Bluetooth API enables browser-based applications to communicate with BLE devices via JavaScript. |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
