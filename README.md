
🚀 FAST DNS HALOTEL TZ 🇹🇿

Copy the script bash to your VPS to run:

```bash
sudo apt update -y && apt upgrade -y 
sudo apt install -y curl && \
curl -fsSL https://raw.githubusercontent.com/iddie15/SLOW-DNS-SCRIPT/main/moded.sh -o moded.sh && \
chmod +x moded.sh && \
sed -i 's/\r$//' moded.sh && \
./moded.sh
