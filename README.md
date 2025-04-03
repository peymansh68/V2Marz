# V2Marz

V2Marz is an Xray-core client for Android devices, designed to work with the Marzban and Marzneshin panels. This project is an example of V2ray_flutter.

Features:
Supported Subscription Links: V2Marz only supports subscription links from Marzban or Marzneshin panels.

Important: Do not attempt to add Vmess://, Vless://, etc. subscription links.

Subscription Handling:

The app reads the subscription URL to fetch account details such as expiration and other necessary information.

For Marzban subscriptions, it fetches the configuration from url/v2ray-json.

For Marzneshin subscriptions, it fetches the configuration from url/xray.

Update Options: The app has a built-in feature to reload subscription data from the URL.

Ping All: The "Ping All" option helps test the handshakes of all configurations, sending them to google.com for verification.

User-Friendly: V2Marz is designed to be simple and intuitive for end-users.

Privacy First: No data collection. No ads.

Marzban Setup:
Link Setup:

Visit Marzban GitHub Repository to get the required template.

JSON Configuration:

After reading the link, place the default JSON file in the following directory:
/var/lib/marzban/templates/v2ray/default.json

No Extra Configuration Needed:

There is no need to add anything else to your .env file. Simply use the uploaded example JSON for rules customization.



