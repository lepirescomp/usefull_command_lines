# usefull_command_lines
Listen to ports, and so on


## Listen to a port:
lsof -i TCP:8000 | grep LISTEN | awk '{print $2}'
