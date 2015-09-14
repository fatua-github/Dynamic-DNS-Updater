# Dynamic-DNS-Updater
Script to update DNS for ClouDNS

Powershell script in early development.   Intended to be scheduled as a job or run as a service to:
- Check last up IP and compare with current external ip
  - if changed update CloudDNS
  - if not changed, check how long since last update.   If greater than configurable date, update
- Check to see if update actually occured
- Email if error
