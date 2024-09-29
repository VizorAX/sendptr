# Vizor.Sendptr

[![Release](https://img.shields.io/github/v/release/VizorAX/sendptr)](https://github.com/VizorAX/sendptr/releases)
[![License](https://img.shields.io/github/license/VizorAX/sendptr)](LICENSE)

> Vizor.Sendptr includes both `vizor.sendptr.exe` and `vizor.recvptr.exe` for efficient, low-latency mouse pointer and event streaming over a network.

🌟 **Key Features**
-------------------

*   📡 **Low-Latency Pointer and Event Streaming**: Stream mouse pointer movements and all associated events, such as clicks and scrolls, in real time.
*   🎯 **Comprehensive Remote Control**: Supports a full range of mouse actions to provide seamless interaction with a remote machine.
*   ⚡ **Optimized for Performance**: Built for efficient handling of mouse events to ensure smooth and responsive control.

📥 **Download and Installation**
-------------------------------

### **Requirements**

*   **Operating System**: Windows 10 or later (Untested on other Windows versions)
*   **Disk Space**: At least 50 MB of free space

### **Dependencies**

*   **None**: Utilizes pure WinAPI functionality.

### **Installation Steps**

1.  **Download the Latest Release**: Get the executables from the [Releases](https://github.com/VizorAX/sendptr/releases) page.
    
2.  **Extract the Package**:
    *   Unzip the downloaded package to your preferred directory.
    
3.  **Run the Executables**:
    *   **To Stream Pointer Events**: `vizor.sendptr.exe <streamer_port> <receiver_address> <receiver_port>`
    *   **To Receive Pointer Events**: `vizor.recvptr.exe <receiver_port> <streamer_address> <streamer_port>`

4.  **Launch the Application**:
    *   After running the commands, the executables will handle the streaming and reception of pointer data and events as per the provided parameters.

📖 **Usage Examples**
---------------------
### Streaming Pointer Data and Events
```bash
vizor.sendptr.exe 5000 192.168.1.100 6000
```
- Streaming pointer data and events from port `5000` to receiver at address `192.168.1.100` on port `6000`.

### Receiving Pointer Data and Events
```bash
vizor.recvptr.exe 6000 192.168.1.50 5000
```
- Receiving pointer data and events on port `6000` from a streamer at address `192.168.1.50` on port `5000`.

🛠️ **Troubleshooting**
-----------------------
If you encounter issues, try the following:

*   **Check for Updates**: Ensure you have the latest version from the [Releases](https://github.com/VizorAX/sendptr/releases) page.
*   **Verify Network Configuration**: Ensure the network settings match on both streaming and receiving ends.
*   **Verify Parameters**: Double-check command-line arguments for correctness.
*   **Contact Support**: Reach out to [sansorich@gmail.com](mailto:sansorich@gmail.com) with details of your issue.

📄 **License**
--------------
This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for more details.

📧 **Contact**
--------------
- **Rodrigo R. S. Sorgato**: [LinkedIn](https://www.linkedin.com/in/rrssorgato) | [Email](mailto:sansorich@gmail.com)
