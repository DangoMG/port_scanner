import socket

def check_port(ip_address, port):
""Returns True if the port is open, False otherwise.""
try:
  s = socket.socket(socket.AF_INET, socket.SOCK_STREAM)
  s.connect((ip_address, int(port)))
  s.close()
  return True
except socket.error:
  return False

def main():
  ip_address = input("Enter the IP address: ")
  port = input("Enter the port number: ")

  if check_port(ip_address, port):
    print("Port {} is open.".format(port))
  else:
    print("Port {} is closed.".format(port))

if __name__ == "__main__"
  main()
