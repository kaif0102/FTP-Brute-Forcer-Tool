# FTP-Brute-Forcer-Tool
FTP Brute-Forcer is a lightweight, multithreaded FTP credential tester written in Python. It tries username/password combinations against an FTP server using multiple worker threads and supports both wordlist-driven and on-the-fly generated password attacks.
Important — Ethical use only: This tool is intended only for authorized security testing, academic study, and defensive research on systems you own or have explicit written permission to test. Unauthorized use is illegal and harmful. By using this project you agree to follow all applicable laws and obtain permission before testing any system.

Features

Multi-threaded FTP login attempts using ftplib.

Accepts a single username or a username list.

Supports password wordlists (from file) or password generation on the fly using configurable charset and length.

Clears remaining tasks and stops workers immediately when valid credentials are found.

Minimal external dependencies (only colorama for colored console output).

Simple CLI interface built with argparse.
Install dependencies:

pip install -r requirements.txt
# or
pip install colorama
