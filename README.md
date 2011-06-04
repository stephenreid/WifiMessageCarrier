# Wifi Message Carrier
Helps provide emergency communication to loved ones from an emergency zone.

When a town is struck by a hurricane, tornado, or tsunami there may not be viable wireless (Edge / 3g / 4g) available locally to send out messages to loved ones to know about survivors / casualties. A pocket wifi (android / pocket router / laptop) device would allow medium range (1500ft) communication (from a first aid / red cross / shelter)

## Runs on
 ### Clients
	- Wifi Smart Phones
	- Laptops
	- PDAs
	- Tablets
	- (anything that has 802.11 and a basic browser)
 ### Servers 
	- Android Phone
	- DD-WRT Routers
	- Laptops (Linux / Unix)
## Interfaces
### Client Interface
	very simple web form web page (depending on client)
	- Sends a message to wifi server
		- To : Phone Number / Email
		- Name: Survivor Name
		- (Status) Injured / Survivor / Casualty
		- Message "I am alright"
### Server Interface
	Very lightweight server (running on the phone)
	- Accept messages (see above)
	- Hosts a hotspot
	- When connected to a connection (ping google.com?) sends database of messages
		- smtp
		- twilio


	
