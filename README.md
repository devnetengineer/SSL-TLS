# SSL-TLS

The terminologies Secure Sockets Layer and Transport Layer Security are interchangeably used. SSL predates the TLS protocol and the industry standard currently is to use TLS v1.2 and above.

At the core of TLS protocol, during its session with the remote server, the following takes place:
1. digital encryption
2. authentication
3. integrity

SSL/TLs will also be used on top of other protocols, such as HTTP, SMTP, etc.

# What is a SSL/TLS certificate?

This is a digital certificate issued by a trusted certificate authority to the person/business that owns the domain. In order to request for one, a Certificate Signing Request (CSR) that contains the information of the person/business has to be submitted, which is then in return used to create a "chain of trust".

