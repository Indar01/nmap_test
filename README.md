import subprocess
ip = input("ip : ")
subprocess.run(["ping", ip])
subprocess.run(["nmap","-sV",ip])
