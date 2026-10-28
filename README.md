# Python MQTT Over Secure Web Sockets (WSS)
This is an example of how to use MQTT from Python over secure web
sockets. Need to install libraries: 
```
uv pip install paho-mqtt dotenv
```

Credentials are stored in a `.env` file with the format of
```
# --- MQTT CONNECTION ---
MQTT_HOST="Your.host.name"
MQTT_PORT="443"
MQTT_PATH="/host-path-to-mqtt"
MQTT_TOPIC = "test/websocket/channel"

# --- AUTHENTICATION ---
MQTT_USER="MQTT-username"
MQTT_PASS="MQTT-password"

# --- ID ---
MOD_NAME="Your-mod-name"
```