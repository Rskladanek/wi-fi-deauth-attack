# Wi-Fi Deauth Attack Tool

**Status:** Work in Progress 🚧

Welcome to the Wi-Fi Deauth Attack Tool project! This tool is designed for cybersecurity enthusiasts to learn about wireless network vulnerabilities by performing deauthentication attacks on Wi-Fi networks in a controlled environment. **Remember: This tool is for educational purposes only. Do not use it on networks you do not own or have permission to test.**

---

## Features

- **Deauthentication Attack:** Disconnect devices from a Wi-Fi network by sending deauth packets.
- **Interactive Menu:** Simple user interface to select targets and actions.
- **Network Scanner:** Identify nearby Wi-Fi networks and connected devices.
- **Logs:** Save attack details for later review.
- **Modular Design:** Clean and reusable code structure.

---

## Planned Features

- GUI support for easier usage.
- Multi-target attacks.
- Automatic return to managed mode after attacks.
- Advanced reporting (e.g., PDF export).
- Support for custom blacklists/whitelists.

---

## How to Use

1. **Install dependencies:**
   ```bash
   pip3 install -r requirements.txt
   ```

2. **Run the tool:**
   ```bash
   sudo python3 main.py
   ```

3. **Follow the instructions:**
   - Enable monitor mode.
   - Scan for networks.
   - Select a target device and router.
   - Start the deauthentication attack.

---

## Requirements

- **Operating System:** Linux (e.g., Kali Linux)
- **Python Version:** Python 3.6+
- **Adapter:** Wi-Fi adapter with monitor mode support
- **Libraries:** [Scapy](https://scapy.net/)

---

## Folder Structure

```plaintext
wi-fi-deauth-attack/
├── README.md            # Project documentation
├── requirements.txt     # Python dependencies
├── main.py              # Main script
├── utils/               # Helper modules
│   ├── monitor_mode.py  # Manage monitor mode
│   ├── deauth.py        # Deauth attack logic
│   ├── scanner.py       # Network scanning functions
│   └── logger.py        # Logging functionality
└── logs/                # Log files
```

---

## Legal Disclaimer

This project is for educational purposes only. Unauthorized use of this tool on networks you do not own or have explicit permission to test is illegal and unethical. The developers are not responsible for any misuse.

---

## Contributing

This is a work in progress! Feel free to suggest features or report bugs. Contributions are welcome via pull requests.

---

## Contact

If you have any questions or feedback, reach out to us through the project repository. Let's collaborate and make this tool even better!

---

Happy hacking (responsibly)! 😎
