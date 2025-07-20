# RISC-V CSR & Debug Analysis Tool

[![Deploy static content to Pages](https://github.com/wipeseals/riscv-reg-analysis/actions/workflows/static.yml/badge.svg)](https://github.com/wipeseals/riscv-reg-analysis/actions/workflows/static.yml)

Web-based tool for comprehensive analysis of RISC-V processor state from XSDB dumps.

## 🚀 Features

- **CSR Analysis**: Detailed breakdown of Control and Status Registers with bit-level visualization
- **Debug Support**: Debug register analysis including DCSR, DPC, and trigger registers  
- **Memory Analysis**: Memory dump parsing and analysis
- **Backtrace Support**: Stack trace analysis from debug dumps
- **Disassembly**: Instruction disassembly analysis
- **URL Sharing**: Share analysis results via compressed URLs
- **Interactive UI**: Dark-themed, responsive web interface

## 📋 Supported Commands

| Command | Description |
|---------|-------------|
| `rrd` | General register dump analysis |
| `rrd csr` | CSR-specific register analysis |
| `bt` | Backtrace/stack trace analysis |
| `dis` | Disassembly analysis |
| `mrd` | Memory read dump analysis |

## 🔧 Usage

1. **Access the tool**: Visit the [live deployment](https://wipeseals.github.io/riscv-reg-analysis/)
2. **Paste XSDB output**: Copy output from supported XSDB commands
3. **Analyze**: Click "Analyze" or press Ctrl+Enter
4. **Share**: Use "Share via URL" to generate shareable links

## 🏗️ Architecture

- **Single-page application**: Pure HTML/CSS/JavaScript
- **No dependencies**: Runs entirely in the browser
- **GitHub Pages**: Automatically deployed on push to master branch

## 📄 License

MIT License - see [LICENSE](LICENSE) file for details.

## 🔗 Links

- [Live Tool](https://wipeseals.github.io/riscv-reg-analysis/)
- [Repository](https://github.com/wipeseals/riscv-reg-analysis)
- [Issues](https://github.com/wipeseals/riscv-reg-analysis/issues)