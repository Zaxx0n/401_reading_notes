# Mimikatz

Mimikatz is an open-source application that allows users to view and save authentication credentials such as Kerberos tickets.  It is often used to steal credentials and escalate privileges.  It is often not even detected by antivirus systems. It is also used by pen testers to detect vulnerabilities.

It consists of the following techniques:
- Pass-the-hash:  Used to  pass hash strings to a target computer to log in.
- Pass-the-ticket: Used to pass a Kerberos ticket to another computer and log in with that user's ticket.
- Overpass-the-hash: Passes a unique key obtained from a domain controller to impersonate a user.
- Kerberoast golden tickets: a ticket attack specifically for KRBTGT accounts. 
- Kerberoast silver tickets: focuses on the TCG ticket to use services on a network.
- Pass-the-cache: Similar to a pass-the-ticket attack, but for Mac/Linux/UNIX.

