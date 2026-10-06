# Async-Local-Net-Scanner

### 🛠 Need Custom Features, Scaling, or Priority Support?
Building a production system or need this tuned for your specific infrastructure? 

* ⚡️ Custom Integration & Anti-Bot Bypass
* 🚀 Dedicated Infrastructure Setup
* 💬 Direct Dev Support: [@Myhamed91](https://t.me/Myhamed91)


📌 DESCRIPTION:
Async Local Net Scanner is a lightweight, ultra-fast asynchronous port scanning utility meticulously engineered for local network diagnostics and host reconnaissance. Built on Python's native asyncio and sockets, it bypasses legacy multi-threaded bottlenecks by implementing concurrent execution pools with strict semaphore limits, providing high-
speed port availability checks without external dependencies.


🚀 HOW TO RUN:
Clone the repository:
Open your terminal, clone the repository, and navigate into the folder:
git clone https://github.com/your-username/async-local-net-scanner.git
cd async-local-net-scanner
Install dependencies:
The core functionality relies entirely on Python's built-in standard libraries (asyncio, sys, typing), requiring zero external pip packages.
Configure & Test:
Run the script directly via Python to execute a default scan against localhost:
python main.py


🛠️ USAGE GUIDE:
To integrate or customize the scanner within your own scripts, import the core asynchronous functions:
import asyncio
from main import scan_ports


⚙ CONFIGURATION:
You can adjust the parameters directly in the script or pass them programmatically:
TARGET_HOST: Target IP address or domain name to scan (default: "127.0.0.1")
TARGET_PORTS: Range or list of integer ports to check (default: range(1, 1025))
CONCURRENCY: Maximum number of simultaneous asynchronous socket connections controlled via Semaphores (default: 100)
TIMEOUT: Connection timeout threshold in seconds for non-responsive ports (default: 1.0)

Saved you some dev hours? Drop a ⭐ to help the project grow!
