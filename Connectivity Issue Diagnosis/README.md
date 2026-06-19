# Assisted Troubleshooting Lab 1 – Connectivity Issue Diagnosis

## Scenario
A work laptop (Home-Laptop) was connected to a home office network but was unable to access the internet. Other devices on the network were available for comparison and testing.

## Problem
The Home-Laptop could not reach external networks, indicating a potential configuration or connectivity issue within the local network setup.

## Troubleshooting Process

### Step 1: Gather Information
- Reviewed Network & Internet settings on Home-Laptop
- Examined IP configuration, subnet mask, and default gateway
- Compared network settings with another device (Home-PC1)

### Step 2: Identify Symptoms
- Confirmed lack of internet connectivity on Home-Laptop
- Observed inconsistencies in IP configuration between devices

### Step 3: Test Connectivity
Used `ping` to test communication with:
- Local devices on the network
- Default gateway
- Other network nodes

### Step 4: Compare with Known Working System
- Checked Home-PC1 network configuration
- Verified correct IP addressing and connectivity
- Used as a baseline to identify misconfigurations

### Step 5: Establish Probable Cause
- Identified incorrect or misconfigured IP settings on Home-Laptop
- Determined this was preventing proper network communication

### Step 6: Implement Solution
- Corrected IP configuration settings
- Ensured proper default gateway and subnet alignment

### Step 7: Verify Functionality
- Retested connectivity using `ping`
- Confirmed successful communication with network devices and internet access restored

## Skills Demonstrated
- Network troubleshooting methodology
- IP configuration analysis (IP address, subnet mask, gateway)
- Use of diagnostic tools (`ping`)
- Comparative troubleshooting between working and non-working systems
- Logical problem-solving and issue isolation

## Key Takeaway
This lab reinforced the importance of verifying IP configurations and using a structured troubleshooting approach to diagnose and resolve connectivity issues efficiently.
