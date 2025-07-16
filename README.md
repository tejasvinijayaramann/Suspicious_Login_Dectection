# Suspicious Login Detection Using Wireshark

## 🧠 Overview
This beginner-friendly cybersecurity project explores how to detect suspicious login-related activity by analyzing TCP traffic using Wireshark.

## 🛠 Tools Used
- Wireshark
- Windows Loopback Interface
- Hex & ASCII Stream Viewer

## 🔍 What I Did
- Opened and analyzed `Digital_Investigation_Task.pcapng`
- Applied TCP filters to isolate loopback traffic
- Inspected packet details and stream data
- Documented findings and observations

## 📸 Screenshot

![Wireshark TCP Filter Applied](screenshots/filter_applied.png)

## 📝 Observations
- All traffic was local (127.0.0.1)
- Packets showed TCP stream behavior with varying sequence numbers
- No external login attempts or credentials detected
- Practiced using Wireshark filters and stream reconstruction

## 🚀 What I Learned
- How to apply filters in Wireshark
- Basics of packet inspection and TCP stream analysis
- How to document forensic findings for a GitHub portfolio

## 🔄 Next Steps
- Capture traffic from a real login page or FTP simulation
- Apply filters like `http.request.method == "POST"` or `ftp.request.command == "USER"`
- Expand analysis to include suspicious behavior and risk indicators



##🔗 Connect with Me
I'm Tejasvini, a cybersecurity learner passionate about digital forensics and compliance.
Let’s connect on LinkedIn or check out more of my work on GitHub!
