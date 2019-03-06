# Get-ADCUnusedObjects
Parse Citrix ADC configuration for Unused Objects

The PowerShell script reads an exported NetScaler ADC Configuration file, parses it for any unused objects (e.g. Server Objects), and outputs a list of "rm" commands to remove the unused objects.
