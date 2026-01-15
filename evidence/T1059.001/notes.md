# Evidence - T1059.001 PowerShell Encoded Command

## What I tested
- Ran PowerShell with encoded/obfuscated command patterns in a Windows lab VM.

## What I expected to see
- Sysmon Process Create (Event ID 1) showing powershell.exe / pwsh.exe with:
  - -enc / -encodedcommand
  - or signs of base64 / Invoke-Expression patterns

## What I observed
- (Fill in) Event source:
- (Fill in) Example CommandLine:
- (Fill in) Screenshot(s) added under screenshots/

## Detection files
- Sigma: detections/sigma/T1059.001_powershell_encoded_command.yml
- KQL: detections/kql/T1059.001_powershell_encoded_command.kql

## Tuning / false positives
- (Fill in) Any legitimate tools/scripts that triggered it in your environment.
