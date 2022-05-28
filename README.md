## Documentation

1. Install samba
2. replace smb.conf dengan smb.conf dari sini
3. jika usb tidak auto mount, lakukan mount manual dengan mengedit file fstab
4. agar komputer terlihat di komputer windows silakan install wsdd
5. Kalo folder yang dishare harus login, dan ketika login terjadi error, maka jalankan perintah
   - `net stop workstation`
   - `net start workstation`
   - jalankan perintah diatas dengan run as admin
