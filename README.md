[Unit]
Description=Serveur Cloud Mamie Flask
After=network.target

[Service]
ExecStart=/usr/bin/python3 /home/foxusgaming/Cloud/cloud_mamie.py
WorkingDirectory=/home/foxusgaming/Cloud
Restart=always
User=foxusgaming

[Install]
WantedBy=multi-user.target
