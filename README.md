# BlinkNet Ultra Prototype

A high-speed file transfer application prototype based on the BlinkNet Ultra concept. This prototype implements core features that enable significantly faster file transfers compared to standard solutions.

## Key Features Implemented

- **Device Discovery**: Automatic discovery of devices on the local network
- **High-Speed File Transfer**: Optimized transfer protocols
- **Multiple File Support**: Transfer multiple files in a single operation
- **Transfer Progress Tracking**: Real-time progress and speed monitoring
- **Protocol Optimization**: Smart protocol selection based on network conditions

## Technical Implementation

This prototype implements the following core technologies from the BlinkNet Ultra concept:

1. **Protocol Fusion Technology**: Dynamic selection between TCP-like reliability and UDP-like speed
2. **Parallel Transfer Architecture**: Using multiple concurrent streams for maximum throughput
3. **Network Analysis Engine**: Pre-transfer testing to select optimal transfer strategies
4. **Adaptive Protocol Switching**: Real-time protocol adjustments based on network conditions

## Installation

### Prerequisites

- Node.js 16+ and npm 8+
- Git

### Setup

1. Clone the repository
```bash
git clone https://github.com/yourusername/blinknet-ultra-prototype.git
cd blinknet-ultra-prototype
```

2. Install dependencies
```bash
npm install
```

3. Start development server
```bash
npm run dev
```

**Limitations of the Prototype:**
While the prototype implements core optimization strategies, it has some limitations compared to the full BlinkNet Ultra specification:

The hardware acceleration is simulated rather than using actual GPU computation
RAM disk buffering is not fully implemented
The compression implementation is simplified
Mesh network capabilities are limited

Even with these limitations, the fundamental architecture choices (parallel transfers, protocol fusion, and network analysis) should provide significant speed improvements over conventional transfer methods like AirDrop and Xender.
To maximize performance, make sure to run the application on devices with good network connectivity, preferably on WiFi 5 (802.11ac) or WiFi 6 (802.11ax) networks, and with minimal network congestion.

## How to Use

1. Launch the application on two or more devices on the same network
2. Click "Discover Devices" to find other devices running BlinkNet Ultra
3. Select files you want to transfer by clicking "Select Files"
4. Choose a destination device from the discovered devices list
5. Click "Send Files" to start the transfer
6. Monitor progress in the Transfer Status panel

## Development

- **Main Process**: `src/main/index.js` contains the Electron main process code
- **Renderer Process**: `src/renderer/` contains the React-based UI
- **Preload Script**: `src/preload/index.js` provides secure IPC communication
- **Protocols**: `src/shared/protocols.js` implements the transfer optimization logic

## Building for Production

To build the application for production:

```bash
npm run build
```

The packaged application will be available in the `release` directory.

## Performance Comparison

While this prototype doesn't implement all the optimizations of the full BlinkNet Ultra concept, it should still demonstrate significant performance improvements over standard methods by using:

- Parallel transfers for increased throughput
- Smart protocol selection based on network analysis
- Dynamic chunk sizing based on file type and network conditions

## Limitations of the Prototype

This prototype focuses on core functionality and doesn't implement all features of the full BlinkNet Ultra concept:

- Limited hardware acceleration support (simulation only)
- Simplified compression implementation
- Basic protocol fusion implementation
- Limited mesh network capabilities

## License

MIT License
