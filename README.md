# NetworkAnomaly Detection for Cyber Threat Identification Using Artificial-Intelligence
A powerful, full-stack web application for analyzing network traffic from PCAP files using machine learning to detect anomalies

Features
🎯 PCAP File Analysis: Upload .pcap and .pcapng files for comprehensive network analysis

🤖 Machine Learning: Uses Isolation Forest algorithm for anomaly detection

📊 Real-time Dashboard: Beautiful web interface with live statistics and visualizations

📈 Multiple Visualizations: Protocol distribution, packet size analysis, anomaly breakdown

📁 Export Options: Download results as CSV, JSON, or HTML reports

🧪 Demo Mode: Test without actual PCAP files using simulated network data

⚡ Fast Processing: Efficient packet processing with progress tracking

🔒 Secure: All processing happens locally on your machine

### One-Click Installation (Recommended)
Clone or download the repository:

```
git clone https://github.com/VedaShivayogi/Network-Anomaly-Detection-for-Cyber-Threat-Identification-Using-Artificial-Intelligence
cd network-analyzer
```

### Project Strucuture
```
network-analyzer/
├── app.py                 # Flask backend server
├── analyzer.py           # Core ML analysis module
├── index.html            # Web interface
├── style.css             # Styling
├── script.js             # Frontend logic
├── requirements.txt      # Python dependencies           
└── README.md            # This file
```
 ### How to Use
 
 <details>
<summary>Show more </summary>
 
1. Upload PCAP File
Drag and drop your .pcap or .pcapng file onto the upload area

Or click to browse and select a file

Or use the demo mode to test with simulated data

2. Start Analysis
Click the "Start Analysis" button

Watch real-time progress in the status indicator

View processing statistics as analysis runs

3. View Results
📊 Statistics Dashboard: See total packets, anomalies, anomaly rate

📡 Protocol Distribution: Breakdown of network protocols

⚠️ Anomaly Breakdown: Types of anomalies detected

🌐 Top Source IPs: Most active source addresses

📈 Visualizations: Interactive charts and graphs

4. Export Results
Download CSV: Full analysis data in spreadsheet format

Download JSON: Raw data for external processing

Generate Report: HTML report with all findings

Save Visualizations: Export charts as PNG images

</details>

### Installation
<details><summary>show more </summary>
  
#### Clone repository
  
git clone https://github.com/VedaShivayogi/Network-Anomaly-Detection-for-Cyber-Threat-Identification-Using-Artificial-Intelligence
cd network-analyzer

#### Install dependencies
pip install -r requirements.txt

#### Optional: For real PCAP analysis
pip install pyshark

</details>

### Run Application
```
python app.py
```

#### Then open: 
http://localhost:5000




