VIPS Leaflet Live Location Demo

Windows CMD commands (run in this folder):
  py -m venv .venv
  .venv\Scripts\activate
  pip install -r requirements.txt
  python app.py

Open http://127.0.0.1:5000

The marker cycles through Chennai, Madurai, Trichy, Chengalpattu and Gojan College every 10 seconds.
Refreshing restarts the sequence. This is simulated demo movement, not real GPS tracking or VPN routing.
Internet access is needed for OpenStreetMap tiles.
