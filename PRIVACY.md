# Qompare Testing Demo · Privacy overview

- **Local documents:** supplier PDFs are read locally. Extracted values, source text, local accounts and comparison history are stored on your device. The application database is not encrypted; protect your Windows account and disk.
- **Local sign-in:** this is a local account, with no email password recovery. The last signed-in account opens automatically until you sign out.
- **Usage statistics:** off by default. If enabled, Qompare sends a random installation identifier, application version and activity time to the Qompare service hosted on Cloudflare.
- **Connection country:** a separate permission, off by default and available only with usage statistics enabled. Cloudflare derives a country code from the connection. Qompare stores that code with the installation statistics, not the IP address, city or precise coordinates. VPNs can affect the result. Disabling country sharing requests deletion of the stored country; disabling statistics requests deletion of the installation statistics. Deletion requires a working connection.
- **Feedback:** only sent on submission. It includes your message, an optional email address, application version and random installation identifier. Do not include confidential quote information.
- **Updates:** checking or downloading updates contacts the Qompare service on Cloudflare. Downloads from GitHub are served by GitHub.
- **Hosting:** online service providers receive connection information, including your IP, as part of serving requests. This does not mean Qompare stores that IP in its statistics database.

This overview describes Testing Demo 0.3.3.
