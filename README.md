# UART (Universal Asynchronous Receiver-Transmitter) in Verilog

## 🧩 Description
This project implements a fully functional UART module in Verilog, complete with:
- Baud rate generator
- Transmitter (TX)
- Receiver (RX)
- FIFO buffering
- Full testbench verification

## 🛠️ Features
- Parametrizable data bits and stop bits
- Baud rate control via configurable timer
- Testbenches for each module
- Waveform outputs for validation

## 📁 Project Structure
```
uart-verilog/
├── README.md
├── LICENSE
├── docs/
│   └── uart_diagram.png
|   └── uart_rx_ASMD.png
|   └── uart_tx_ASMD.png          
├── src/
│   ├── uart.v
│   ├── uart_rx.v
│   ├── uart_tx.v
│   ├── baud_rate_gen.v        
├── tb/
│   ├── uart_tb.v
│   ├── uart_rx_tb.v
│   ├── uart_tx_tb.v
│   └── waveforms/
│       ├── uart_rx_waveform.png
│       └── uart_tx_waveform.png
├── sim/
│   └── (any simulation scripts or results)
```

