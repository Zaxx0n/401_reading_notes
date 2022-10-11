# CIA Triad and File Transfer
The CIA triad are Confidentiality, Integrity and Availability. To have a secure system these must be met.

Confidentiality is restricting access to data to only those that need it.  This can protect trade secrets, salaries, list of customers, products in development etc.  In firms, this can keep attorney-client privilege.  In healthcare, it is used to comply with HIPAA/HITECH and secures ePHI.

When sharing data over the internet, the confidentiality of the data becomes vulnerable. 

Next in the triad,is Integrity. This is specifically for data and preventing it from being tampered with.  Just like confidentiality, Integrity is vulnerable during data transfers.  One example is "man-in-the-middle" or "on-path" attacks, where someone can sit in the middle of a data transfer and alter the data. 

Last in the triad is Availability.  This is making sure that your data is accessible.  Power interruptions, network disruptions, server failures, DDoS and many other environmental factors can render data inaccessible.  This can be extremely serious if it involves business-critical data.  

Solutions for data that is in transit include SSL or SSH.  Data at rest is usually kept safe through file encryption. 2-factor authentication can help secure data and keep it confidential. Hashing and digital signatures are good uses for keeping the integrity of data.  

Clusters and failover servers are a good way to keep the availability of data. 

