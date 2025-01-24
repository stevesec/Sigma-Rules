# Sigma Rules Repository

## Overview
Custom Sigma rules for detecting security threats and suspicious activities across various environments.

## Repository Contents
- Detection rules for:
  - Remote Desktop Software Downloads
  - Active Directory Reconnaissance Tools
  - Other specific threat detection scenarios

## Sigma Rule Details
- **Status**: Experimental/Test
- **Platforms**: Primarily Windows
- **Detection Techniques**: 
  - Filename matching
  - Keyword detection
  - Event log analysis

## Usage
1. Import rules into your SIEM or log analysis platform [Aurora Agent](https://www.nextron-systems.com/aurora/)
2. Tune rules to match your specific environment
3. Adjust false positive filters as needed

## References
- [Sigma Rule Format](https://github.com/SigmaHQ/sigma)
- [MITRE ATT&CK Framework](https://attack.mitre.org/)

## Disclaimer
- Rules provided as-is
- Requires validation in your specific environment
- Periodic review and updates recommended

## Contributing
- Open to pull requests
- Please include test cases and context for new rules
- Please feel free to add more test cases that you see to any Sigma Rules here

## License
[Your License Here]