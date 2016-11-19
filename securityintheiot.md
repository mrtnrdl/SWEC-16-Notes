# Security in the IoT

## Why
- privacy
- physical safety
- keeping the internet working

## State of IoT security
- FiatChrysler remote pwning connected cards
- ddos of dyn with the mirai (toolkit)[https://krebsonsecurity.com/2016/10/source-code-for-iot-botnet-mirai-released/]
- Currently, the state of iot security is bad.

### Problems
- A lot of the devices can't be updated
- ~5 Million devices going online *every day*
- The Internet of unpatchable devices (Akamai)

### Who are the attackers
- security researchers
- script kiddies
- competitors
- criminals
- etc etc

## How to do it right
- http polling: you might get hacked but at least you notice it...
- unfortunately, it has a lot of issues
- traffic volume and latency would be affected

### better than http polling
- http long polling
- web socket
- raw tcp?
- message routing!

## Security with crossbar.io
- no open ports
- connection to the router
- wide range of authentication methods

## Principles of network attack surface minimalization
1) there must not be any listening port on a device
2) all application code must be seperated from network server code


## Questions and Answers

### Ease of use is important for end users, how do you solve that with a central router?
- Providers maintain the infrastructure
- end users don't even realise it
- end users run default
- devices won't get updated --> that's why security is in the domain of the provider.

### Replacement Cycles of devices
- closed source software won't get updated forever
- updates will stop at some time for the devices

### Are there similar strategies to police etc in the cyberspace?
- Governments are trying. 
- They lack the knowledge and the budget.

 ## Wrap up
 - There are way more questions than answers at the moment.
 - Governments lack capabilities
 - The people need to learn about these things - children don't learn principles about it, computers, security etc....
 - monkey see, monkey do. 
