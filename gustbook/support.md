# Gustbook Support

Need help or found a problem? Email mustafalpyilmaz0@gmail.com and you'll get a reply within two business days.

## Set the hub's server name by hand
Gustbook sets the server name for you. If it cannot reach your hub, set it this way:
1. Find your hub's IP address in your router's list of devices.
2. On your Mac, open Terminal and run `curl -d 'ser=192-168-1-42.sslip.io' http://192.168.1.20/config.cgi`.
   Use your Mac's address in the name, with dashes for dots. Use your hub's address at the end.
3. The hub restarts. Its next upload goes to Gustbook.

To point the hub back to AcuRite, run `curl -d 'ser=atlasapi.myacurite.com' http://192.168.1.20/config.cgi` with your hub's address.

## Common questions

**Why does the hub need my Mac to be on?**
The hub sends its readings to your Mac, and Gustbook passes them on to AcuRite. While Gustbook is not running, AcuRite gets no readings. Turn on "Start Gustbook at login" in Settings > General.

**How do I export my history from My AcuRite?**
On myacurite.com, open your device and click Export Data. My AcuRite emails a download link. In Gustbook, click Import and choose the downloaded CSV.

**How do I restore my purchase?**
Open a chart range marked with a lock, or click Export, then click "Restore purchase" in the Gustbook Pro sheet. Use the same Apple Account you bought with.

**How do I get a refund?**
Refunds are handled by Apple: https://reportaproblem.apple.com

**Where is my data stored?**
On your Mac. See the privacy policy: https://mustafalpyilmaz.github.io/studio-legal/gustbook/privacy-policy.html
