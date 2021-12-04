import paramiko
import paramiko as paramiko
from pip._internal.network import session

ip = '192.168.31.128'
port = 22

def ssh_connection(ip):'192.168.31.128'
host = '192.168.31.128'
username = 'L00170250'
password = '1234'
client = paramiko.SSHClient()
client.load_system_host_keys()
client.set_missing_host_key_policy(paramiko.AutoAddPolicy())

print("Establishing a connection...")
