# brother_printserver_for_pi
This is a little tutorial for people with Brother printers, who would want to use it with CUPS on a raspberryPi.

1. Update & Install CUPS
sudo apt install -y build-essential git autoconf libtool cups libcups2-dev libcupsimage2-dev

2. Install Drivers
sudo apt-get install printer-driver-brlaser

3. CUPS remote access
sudo cupsctl --remote-any
sudo usermod -a -G lpadmin <your-username>

4. Add Printer on the WebUI
You can access CUPS @ https://Your Pi's Adress:631
If you cant find the exact model of your printer, try to select the closest one on the list.

6. Enjoy
