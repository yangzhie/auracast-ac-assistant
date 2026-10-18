# Auracast Auto-Connection
Sample auto-connects to a sink near the BAP Scan Delegator, searches for a broadcast source, recieves decisions from a companion and adds the broadcast ID to the BAP Scan Delegator via BASS.
## Requirements
- Board with BLE 5.2 support
- Broadcast Sink
- Broadcast Source
## Usage
1. Flash sample onto nRF board.
2. Erase any previous connections of the sink, and turn it on near the board.
3. Use the [Auracast Companion application](https://github.com/yangzhie/auracast-companion) to forward decisions/commands to the board.
## Design
This sample was a proof-of-concept extension built on top the BAP Audio Assistant from Nordic. It was created and designed for Nordic's nRF52840 board and has not been tested with any other board.