# StackViz

A Visual Studio Code extension that provides real-time visualization of function call stacks. StackViz generates interactive tree visualizations of function executions, making it easier to understand program flow, debug complex call chains, and teach programming concepts.

## Features

- Real-time visualization of function call stacks
- Interactive tree diagram showing function calls and their relationships
- Parameter and return value tracking for each function call
- Support for multiple programming languages
- Customizable visualization themes
- Perfect for understanding:
  - Function call hierarchies
  - Recursive functions and algorithms
  - Program execution flow
  - Complex debugging scenarios
  - Dynamic programming patterns
  - Callback chains

## Installation

1. Open Visual Studio Code
2. Go to the Extensions view (`Ctrl+Shift+X` or `Cmd+Shift+X`)
3. Search for "StackViz"
4. Click Install

## Usage

1. Open your project file
2. Place breakpoints in functions you want to visualize
3. Start debugging your code
4. The StackViz panel will automatically appear on the right side
5. Watch the call stack tree update in real-time as functions are called and return

## Technical Details

Built with:
- Rust 🦀
- WebAssembly (Wasm)
- VS Code Extension API

## Development

### Prerequisites

- Rust toolchain
- wasm-pack
- Node.js and npm
- Visual Studio Code

### Building from Source

```bash
# Clone the repository
git clone https://github.com/rhasanm/stack-viz
cd stack-viz

# Install dependencies
npm install

# Build Rust to WebAssembly
wasm-pack build

# Build VS Code extension
npm run build
```

### Testing

```bash
npm run test
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## Roadmap

- [ ] Support for asynchronous function call visualization
- [ ] Add support for more programming languages
- [ ] Implement step-by-step playback of call sequences
- [ ] Add ability to export visualizations
- [ ] Create interactive tutorials
- [ ] Add memory usage visualization
- [ ] Support for parallel execution visualization
- [ ] Performance profiling integration
- [ ] Custom visualization layouts
- [ ] Integration with popular debugging tools

## License

[MIT](https://choosealicense.com/licenses/mit/)

## Acknowledgments

- Inspired by the need to make program execution flow more visible and understandable
- Built with love for the development and education community
