Open 6 terminals:
			1 for master_server
			2 for client
			and rest 4 for chunk_servers


Now first run all 4 chunk_servers by the command:
							python3 chunk_server.py	6467
							python3 chunk_server.py	6468
							python3 chunk_server.py	6469
							python3 chunk_server.py	6470


							python3 Master_server.py

							python3 client.py
