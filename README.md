# 📊 Netdata Monitoring Dashboard

# 🎯 Goal
Set up a basic system health monitoring dashboard using Netdata, and automate setup, testing, and cleanup with shell scripts.

# ✅ Features

1. Real-time monitoring: CPU, Memory, Disk I/O

2. Web-based dashboard (port 19999)

3. Custom dashboard chart/visual modification

4. Alert for CPU usage > 80%

4.1 Automated scripts:

4.2 setup.sh: Install Netdata

4.3 test_dashboard.sh: Generate system load

4.4 cleanup.sh: Uninstall Netdata

# 📦 Usage

1. Install Netdata
chmod +x setup.sh && ./setup.sh

2. Access Dashboard
Open in browser: http://<your-ip>:19999

3. Test Monitoring
chmod +x test_dashboard.sh && ./test_dashboard.sh

4. Customize Dashboard
Edit config in /etc/netdata/

5. Set Alert
Configure alert in /etc/netdata/health.d/

6. Cleanup
chmod +x cleanup.sh && ./cleanup.sh
