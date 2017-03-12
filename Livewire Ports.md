
Port	|Protocol	|Multicast Address	|Purpose	Notes
67, 68	|UDP		|BOOTP Server/Client	|Remote IP address assignment
93	|TCP		|Livewire Routing Protocol	Also provides transparent passing of custom messages, similar to the Ancillary Data Transmission feature of AES3
123	|UDP		|Network Time Protocol	
514	|UDP		|Syslog	Activity logging to a syslog receiver.
2055	|UDP	\239.192.255.4	Multicast-based GPIO (CMsg2 protocol)	GPIO commands, GPIO node ? console-type endpoint
2060	|UDP	|239.192.255.4	Multicast-based GPIO (CMsg2 protocol)	GPIO commands, console-type endpoint ? GPIO node
4000	|UDP	|	Livewire Advertisement and Source Allocation Protocol	Verbose advertisement and source allocation requests
4001	|UDP	|239.192.255.3	Livewire Advertisement and Source Allocation Protocol	Periodic and verbose announcements Source allocation state announcements and responses
4002	|UDP	|239.192.255.3	Engine Supervision Protocol	
4010	|TCP	|	Livewire Control Protocol	
4011	|UDP	|239.192.255.4	LWCP for Accessory Modules	Module to Console
4012	|UDP	|239.192.255.3	LWCP for Accessory Modules	Console to Module
5004	|UDP	|239.192.x.x	RTP Livewire Audio	Last two address octets pertain to Axia channel ID, e.g. 9999 = 39 15 (hex 27 0F)
7000	|UDP	|	|Livewire Clock	One device assigns itself as LAN-wide reference, all other devices slave to it
9997	|TCP	|	|Protocol logging	Debug protocol logging for Element