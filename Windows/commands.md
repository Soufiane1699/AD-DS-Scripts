# Ausgabe ob SMBv1 und SMBv2 aktiv sind Ausgabe in Form von True oder False
Get-SmbServerConfiguration | Select-Object EnableSMB1Protocol, EnableSMB2Protocol

# SMB höchste Versions Ausgabe
Get-SMBConnection | Select-Object Dialect
