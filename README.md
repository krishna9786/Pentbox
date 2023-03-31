# Pentbox
#how to install a payload

1. Open a terminal window in Kali Linux.
Update the package lists by running the following command:
sudo apt-get update

2. Install the dependencies required for Pentbox by running the following command:
sudo apt-get install build-essential libssl-dev libnetfilter-queue-dev libpcap-dev

3. Download the Pentbox source code from the official website (http://www.pentbox.net/) or from its GitHub repository (https://github.com/whitehatpanda/pentbox-1.8). You can use the following command to download the source code from GitHub:
git clone https://github.com/whitehatpanda/pentbox-1.8.git

4. Change to the directory where the Pentbox source code was downloaded, and compile it by running the following commands:
cd pentbox-1.8

5. After the compilation is complete, you can run Pentbox by running the following command:
sudo ./pentbox.rb
