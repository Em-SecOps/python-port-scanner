import socket


def scan(target, ports):
        print('\n' + ' Starting scan for ' + str(target))       
        for port in range(1, ports):
                 scan_port(target, port)

def scan_port(ipaddress, port):
    try:
        sock = socket.socket()
        sock.connect((ipaddress, port))
        print("[+] Port opened " + str(port))
        sock.close()
    except:
        pass

target = input("[*] Enter Target to scan(split them by ,): ")
ports = int(input("[*] Enter the number of ports to scan: "))

if ',' in target:
    print("[*] Scanning multiple targets: ")
    for ip_addr in target.split(','):
        scan(ip_addr.strip(' '), ports)
else:
    scan(target, ports)
