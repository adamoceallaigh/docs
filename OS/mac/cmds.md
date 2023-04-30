# Documentation: Macos commands

`history`: Retrieves a list of commands executed in the recent past

`grep ? ~/.(zsh|bash)_history`: back searches for ? throughout devices terminal history

`kill -9 $(lsof -ti:?)`: find and kill processes running on specific port, where ? is the port number utilized

`kill -9 $(lsof -ti:/,?)`: find and kill processes running on specific ports, where / and ? are the port numbers utilized. List can be extended with commas between.

`npx kill-port ?`: kills processes running on specified port using `kill-port` library, where ? is the port number utilized

`npx kill-port / ? -`: kill processes running on specific ports using `kill-port` library, where /, ?, and - are the port numbers utilized. List can be extended with spaces between

`find . -name ".DS_Store" -delete`: finds and deletes all the files named .DS_Store in the current path

`pwd`: prints the current working directory