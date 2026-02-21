# Hud
Elevate your FiveM server with the Vertex Studio HUD – a sleek, modern, and fully customizable interface. Display health, armor, money, vehicle stats, and more in real-time. Lightweight, performance-friendly, and designed for immersive gameplay on any server.

How to Install Vertex Studio Custom HUD in FiveM

Requirements:

A FiveM server (FXServer) running on your machine or host

Basic knowledge of server file structure and resource management

Step 1: Download the HUD

Obtain the custom HUD files from Vertex Studio. Typically, this will be a .zip or folder containing all HUD scripts, assets, and configuration files.

Step 2: Add HUD to Server Resources

Extract the HUD folder into your server’s resources directory.

Example path: server-data/resources/[hud]/vertex_hud

Step 3: Configure server.cfg

Open your server.cfg file.

Add a line to start the HUD resource:

ensure vertex_hud

Save the file.

Step 4: Adjust Settings (Optional)

Open the HUD’s config file (often config.lua or settings.json) to customize:

Colors and icons

Position of elements

Enabled/disabled modules (health, armor, hunger, etc.)

Step 5: Restart Server

Restart your FiveM server to load the new HUD.

Join the server and verify the HUD appears correctly and updates in real-time.

Step 6: Test Functionality

Check player stats, notifications, and other HUD elements.

Make adjustments in the config file if elements overlap or need tweaking.

Tips:

Backup your server before adding new resources.

Keep the HUD resource updated with Vertex Studio releases for bug fixes and improvements.
