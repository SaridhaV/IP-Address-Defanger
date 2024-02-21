# IP-Address-Defanger
The "IP Address Defanger" project aims to create a tool or program that sanitizes or defangs IP addresses, primarily for security purposes. The term "defanging" in this context refers to modifying an IP address in such a way that it cannot be directly interpreted,thereby reducing the risk of unintentional execution or exploitation.
def defang_ip_address(ip_address):
    defanged_ip = ip_address.replace('.', '[.]')
    return defanged_ip

# Example usage:
ip_address = input("Enter the IP address: ")
print("Original IP address:,{ip_add/ress}")
defanged_ip = defang_ip_address(ip_address)
print("Defanged IP address:", defanged_ip)

