## Rationale
'TRMNL Local Web Server' is a local web server designed to serve local content (BMP image) to a TRMNL client e-ink display. It simulates the TRMNL cloud server (https://usetrmnl.app/). The server is built using Flask and supports serving BMP images, logging requests, and updating configuration settings.

Very small change in Firmware of TRMNL needed.

original: #define API_BASE_URL "https://trmnl.app" 

change to: #define API_BASE_URL "https://<your_ip>:83" 

## How to use

1. basic configuration needed for path to image
2. optional parameters having defaults
3. open the status webpage at https://homeassistant:83 