# Pedri-dnstt
An accurate dns scanner for DNSTT tunneling


Install pedridns using wget:
wget https://raw.githubusercontent.com/pedridns/pedri-dnstt/main/pedridns

chmod +x pedridns

./pedridns -h 

Now, let's get started:

Usage:
./pedridns -h
This will display help for the tool. Here are all the switches it supports.

A tool that accurately hunt perfect dns servers for DNSTT tunnel by scanning IP ranges.

   -p [n]         : max. number of processes (default: 0)
   -o <filename>  : output the working IP's in a file while dumping to stdout
   -h             : show this message
   -d             : set custom domain (default: google.com)

Possible IP formats:
   xxx.xxx.xxx.xxx (e.g 192.168.0.1)
   xxx.xxx.[0-255]-[0-255].[0-255]-[0-255] (e.g 192.168.10-15.0-255)
   xxx.xxx.xxx.[0-255]-[0-255] (e.g 192.168.0.0-255)
   xxx.xxx.[0-255]-[0-255].xxx (e.g 192.168.10-15.1)
   xxx.xxx.xxx.xxx/[16-32] (e.g 192.168.0.0/24)


Running pedridns

pedridns -d your-domain in dnstt or use google.com 8.8.8.0/24 exemple 

t.me/@pedridns 
