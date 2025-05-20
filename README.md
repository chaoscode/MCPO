# MCPO Docker Compose with Web-Based Config Editor
This Docker Compose configuration is optimized for Dockge deployment and includes an integrated web-based text editor for managing MCPO's config.json file.
Key Features:

Built-in web editor for real-time configuration editing
JSON validation to prevent syntax errors
Persistent configuration storage via Docker volumes

Important Security Notes:

Change the default password from "changeme" to a secure password before deployment
Update the MCPO_API_KEY from the default "test" value to a strong, unique API key

Service Ports:

Config Editor: http://your-server-ip:18020
MCPO Server: http://your-server-ip:18021

Quick Start:

Update the config in the .env file
Deploy services
Access the config editor to customize your MCPO settings
Restart MCPO container after making configuration changes
