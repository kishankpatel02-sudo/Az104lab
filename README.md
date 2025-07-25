
---

## VM Details

- **VM Names:** vm2, vm3
- **Frontend Ports:**
  - 33891 → vm2
  - 33892 → vm3

## Load Balancer

- Type: **Standard**

## Network Security Group (NSG) Rules


---

## VM Details

- **VM Names:** vm2, vm3
- **Frontend Ports:**
  - 33891 → vm2
  - 33892 → vm3

## Load Balancer

- Type: **Standard**

## Network Security Group (NSG) Rules

- NSG rules were added **manually** to allow inbound RDP traffic on the specified frontend ports.
- NSG rules were added **manually** to allow inbound HTTP traffic on the specified frontend ports.

## Troubleshooting

- Encountered **RDP 0x204 error** initially.
- Issue was resolved by correcting the **target port** in the NAT rule configuration.

## Screenshots

Screenshots are included in the `images/` folder for visual guidance.

---

## How to Use This Lab

1. Review the NSG and Load Balancer settings.
2. Verify VM availability and ensure the load balancer is properly configured.
3. Use RDP client to connect using the frontend IP and respective port.
4. Refer to the troubleshooting section if connection issues arise.

---

Feel free to explore and modify this setup to suit your environment!

---

*Created by [Your Name]*  
*Date: [Date of Creation]*  

## Troubleshooting

- Encountered **RDP 0x204 error** initially.
- Issue was resolved by correcting the **target port** in the NAT rule configuration.

## Screenshots

Screenshots are included in the `images/` folder for visual guidance.

---

## How to Use This Lab

1. Review the NSG and Load Balancer settings.
2. Verify VM availability and ensure the load balancer is properly configured.
3. Use RDP client to connect using the frontend IP and respective port.
4. Refer to the troubleshooting section if connection issues arise.

---

Feel free to explore and modify this setup to suit your environment!

---

*Created by Kishan Patel*  
*Date: 25/07/2025*  
