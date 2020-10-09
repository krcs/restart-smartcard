# make-openssl
Powershell script for reinstalling smartcard drivers.

I use this script when I need to switch between gpg and opensc. 
When using openvpn (opensc) and authentication in ssh (gpg) I don't need to disconnect and reconnect my yubikey every time.
Tested with yubikey and nitrokey.

#### Requirements
- Windows Device Console (devcon.exe) (https://docs.microsoft.com/en-us/windows-hardware/drivers/devtest/devcon)

#### Usage
  `.\restart-smartcard.ps1`
