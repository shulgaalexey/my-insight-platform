# Learning Insight Platform

## InsightIDR

### Installation

Lab 1, at 11:00
1. Goto IIDR
2. Goto Data Collection
3. Setup Collector
4. Download Collector
5. Goto props of the installer, click “Unblock”
6. Run installer
7. Save Agent Key
    (Program Files -> Rapid7 -> Collector -> agentKey -> Agent_Key.html)
8. Click Data Collector
9. Setup Collector -> Activate Collector
10. Enter good name and agent key

Check connection:
curl -Is https://eu.data.insight.rapid7.com | head -1
curl -Is https://s3.eu-central-1.amazonaws.com | head -1
curl -Is https://eu.ndpoint.ingress.rapid7.com | head -1



0917
