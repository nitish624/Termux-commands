# Hosting by python
- pkg install python
- python -m http.server 8080 &
- cloudflared tunnel --url http://localhost:8080