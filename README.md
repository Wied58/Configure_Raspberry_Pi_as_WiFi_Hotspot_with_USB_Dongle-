To update your GONet...

Install Ansible and Git localy on your pi: sudo apt-get install ansible git -y

If that commad errors, please update Raspian with: sudo apt-get update  -y &&  sudo apt-get upgrade  -y

To run the Playbook:

export HOME_WIFI_SSID="YourHomeSSID"
export HOME_WIFI_PASSWORD="YourHomePassword"

ansible-pull -d /home/pi/pull -i 'localhost,' -U https://github.com/Wied58/Configure_Raspberry_Pi_as_WiFi_Hotspot_with_USB_Dongle- Configure_Raspberry_Pi_as_WiFi_Hotspot_with_USB_Dongle.yml


