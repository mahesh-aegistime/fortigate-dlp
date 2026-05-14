## Important Warning
Before applying any configuration:

- Take a full FortiGate backup
- Test in a lab environment first
- Validate regex patterns before production deployment
- Use monitor mode before enabling block/quarantine actions
- Review firewall policies after applying DLP sensors
- Incorrect DLP configuration may impact production traffic

## Backup Recommendation

Always take a full FortiGate configuration backup before importing or modifying DLP settings.
# FortiGate Advanced DLP Rules

Custom FortiGate DLP dictionaries, regex patterns, and sensors for detecting sensitive Indian identity data and medical/hospital information.

## Features
- Aadhaar Number Detection
- PAN Card Detection
- Voter ID Detection
- Medical & Hospital Keywords
- Patient Record Protection
- Regex-Based Inspection
- Advanced DLP Sensors
- FortiGate CLI Ready Configurations

## Included Detection Categories

### Indian Identity Data
- Aadhaar Number
- PAN Number
- Voter ID / EPIC Number

### Medical / Hospital Data
- Patient Records
- Clinical Notes
- Treatment Plans
- Lab Reports
- Prescriptions
- Medical Billing
- Insurance Claims
- EMR / EHR Keywords

## Supported Platforms

- FortiGate 7.4.x
