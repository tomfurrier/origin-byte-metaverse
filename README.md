# origin-byte-metaverse

# Client & Server Build guide
1. Set Network Address in  Network Manager Component to your server url like eu-west.ssl.cloud.playflow.app

2. Put in your PlayFlow port from https://app.playflowcloud.com/ into your SimpleWebTransport. 

3. Uncheck the “SSL enabled” check box in your Simple Web Transport and make sure “client use wss” is checked.

3. Upload Server.

4. Start Server with Enable SSL checked in the PlayFlow Cloud Window.

5. Change Port in SimpleWebTransport component to the SSL port returned in PlayFlow logs

6. Hit Play - works from Editor

7. Switch to WebGL (or other) platform if needed

8. Build