# Load-Testing-DoS-Tool

## About:
Lightweight, no-deps Python script that spins up N concurrent workers to hammer any URL you feed it.  
CLI prompts for target list & thread count, randomized POST payloads & user-agent rotation, optional HTTP/SOCKS proxy support, and clean logging.

> **Important:** This tool is provided for **authorized** load- and stress-testing only. **I AM NOT RESPONSIBLE FOR ANY ACTIONS YOU TAKE WHILE USING MY SOFTWARE** Do **NOT** run it against services you do not own or do not have explicit written permission to test. Unauthorized use may be illegal and unethical.

## Proxy Format:
Accepted proxy formats:
- `user:pass@ip:port`
- `ip:port`

Supports HTTP(S), SOCKS4, and SOCKS5 proxies when configured. Proxy quality matters 

### Links
Project repo | [https://discord.com/invite/YMDR7yQC5W] 

## Features / Captures:
- Lightweight, dependency-free Python script (works with standard Python)
- CLI prompts for target list & thread count
- Randomized POST payloads and rotating User-Agent headers
- Optional HTTP/SOCKS proxy support (user-provided)
- Clean, timestamped logging of progress and responses
- Designed for quick, ad-hoc authorized tests against staging/owned endpoints

## Installing:
**SUPPORTED PLATFORMS:** Tested on Windows, macOS, and Linux (Python 3.8+)

### Quick install
Make sure you have [python](https://www.python.org/downloads/) and [git](https://git-scm.com/download/) installed.

```bash
git clone https://github.com/YourUsername/Load-Testing-DoS-Tool
cd Load-Testing-DoS-Tool
# no external deps; just run with your system Python
python main.py
