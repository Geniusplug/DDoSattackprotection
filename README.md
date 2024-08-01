<h3>IP Tracking:</h3></br>The script tracks each IP address's request count and timestamps. If an IP exceeds the REQUEST_LIMIT within the TIME_WINDOW, it gets blocked with a 429 Too Many Requests error.
<h3>Resetting Counts:</h3></br> The request count resets if the time since the last recorded request exceeds the TIME_WINDOW.
<h3>Basic Simulation:</h3> </br>This is a simple simulation for educational purposes and may not fully protect against complex DDoS attacks. For real-world scenarios, you would need more robust solutions.
