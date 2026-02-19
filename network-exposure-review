# Network & Service Exposure Review

## Listening Services

The system is running several local services bound primarily to loopback interfaces (127.0.0.1 and ::1), including:

- Local DNS resolver (port 53)
- CUPS printing service (port 631)
- mDNS (port 5353)
- NTP (port 323)

No externally bound TCP services were identified during enumeration.

## Firewall Status

The Ubuntu Uncomplicated Firewall (UFW) is installed but currently inactive.

Status: inactive

## Risk Assessment

Although no externally exposed services were observed, the absence of an active host-based firewall increases risk if:

- Network mode changes (e.g., bridged adapter)
- Additional services are installed
- System is connected to an untrusted network

## Recommendation

Enable UFW with a default deny inbound policy:

sudo ufw default deny incoming  
sudo ufw default allow outgoing  
sudo ufw enable
