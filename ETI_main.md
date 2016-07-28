IP Addresses and Ports
===================
At first the participant must establish a **TCP/IP** session to the **Connection Gateway** — the
**IP/port numbers** are provided by the exchange. Participants will be provided with a *Primary*
and *Secondary* Connection Gateway address via the member portal. If the connection to the
primary Connection Gateway fails, participants should connect to the secondary Connection
Gateway.
> **Note**
Once that connection is established, the participant sends a Connection Gateway Request
message. The Connection Gateway will validate PartyIDSessionID (20055) and Password
(554), which are parameters provided by the exchange. The Connection Gateway cannot be
used for any other purpose.
