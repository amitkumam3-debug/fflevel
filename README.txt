Folder layout (put everything in ONE folder):

  Main.py
  dashboard_server.py      <- replace with this one
  templates/index.html     <- replace with this one
  message_ids.py, thunderFF_pb2.py, devices.json, requirements.txt, token_cache.json

Run:
  pip install -r requirements.txt
  python Main.py

Open: http://localhost:20335
(On a VPS/host: http://YOUR-SERVER-IP:20335 and open port 20335 in the firewall.)
