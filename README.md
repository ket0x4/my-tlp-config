# My TLP config
This file configured for:
- AMD ryzen 3 2200U laptop with Vega 3 GPU, 8GB DDR4 2600 Mhz RAM, 240GB NVME SSD.

If you have similar system feel free to use.If you don't, Don't use this config!

To use this config: 
1. Install TLP
2. Copy tlp.conf to /etc/ (`su -c "cp tlp.conf /etc/"`)
3. `systemctl enable tlp && systemctl start tlp`
4. `su -c "tlp start"`
