# powershell

- `$PSVersionTable` shows the running version.
- `Get-Command foo` is the equivalent of `which foo`.
- `Out-File -Encoding utf8` to avoid the default UTF-16 BOM.
- `Get-History | Select -Last 5` shows recent commands of this session.
- `$ErrorActionPreference = 'Stop'` makes scripts halt on first error.
- `Invoke-WebRequest` returns objects, `curl.exe` returns plain text — pick on purpose.
- `Get-History | Select -Last 5` shows recent commands of this session.
- `Start-Transcript` records the whole session to a log file.
- `Format-Hex` inspects bytes of a string or file.
- `-WhatIf` previews destructive cmdlets before running.
- `Invoke-WebRequest` returns objects, `curl.exe` returns plain text — pick on purpose.
