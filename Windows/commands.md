### Ausgabe ob SMBv1 und SMBv2 aktiv sind Ausgabe in Form von True oder False
Get-SmbServerConfiguration | Select-Object EnableSMB1Protocol, EnableSMB2Protocol

### SMB ausgabe der unterstützen Versionen
Get-SMBConnection | Select-Object Dialect

### Domäneninformationen herausfinden
Get-ADDomain

