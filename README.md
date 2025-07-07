# 📶 5G NR - Physical Layer Simulation

This project simulates essential aspects of the **5G New Radio (NR)** physical layer using Python. It covers key components like data generation, channel coding (LDPC), modulation schemes (QPSK/16QAM), MIMO concepts, and basic channel models.

---

## 🚀 Features

- **Bitstream Generation**: Random binary data source for simulation.
- **LDPC Encoding/Decoding**: Implements Low-Density Parity-Check coding as per 5G NR specs.
- **Modulation Schemes**: QPSK and 16-QAM modulation support.
- **OFDM Waveform Generation**: Orthogonal Frequency Division Multiplexing baseband simulation.
- **AWGN Channel Simulation**: Adds noise to test performance under real-world conditions.
- **BER Calculation**: Bit Error Rate estimation for performance analysis.

---

## 🛠️ Tech Stack

- **Language**: Python 3.x
- **Libraries Used**:
  - `numpy`
  - `scipy`
  - `matplotlib`
  - `ldpc` (for LDPC encoding/decoding)

---

## 📁 Folder Structure

5G_NR/
- ├── bit_stream.py # Generates binary bitstream
- ├── ldpc_encoder.py # LDPC encoder logic
- ├── qpsk_modulator.py # Modulation logic
- ├── mimo_channel.py # MIMO channel simulation
- ├── ofdm_generator.py # OFDM waveform creation
- ├── awgn_channel.py # Noise model
- └── ber_calculator.py # Computes BER

