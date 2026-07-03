vpn_security_system/
├── main.py                  # CLI entry point
├── requirements.txt
├── LICENSE
├── src/
│   ├── vpn_client.py         # Connection lifecycle, IP masking, data transfer
│   ├── encryption.py         # AES-based encryption engine
│   ├── threat_detector.py    # Blocklist checks + simulated threat scanning
│   └── logger.py             # Centralized security event logging
├── tests/
│   └── test_vpn.py           # Unit tests
└── logs/                      # Generated at runtime
git clone https://github.com/<your-username>/vpn-security-system.git
cd vpn-security-system
pip install -r requirements.txt
python main.py
