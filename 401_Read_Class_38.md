# Burpe Suite

Burpe Suite is a set of tools that were designed to help pentesting of web applications.  It can use both HTTP and HTTPS.  Its primary tool is a proxy.  This proxy has been designed to analyze web traffic.  It intercepts requests and responses, reading and allowing them to be edited in real time.

Much of Burp is used with the proxy.  It has multiple functions, one is Intruder which allows the user to configure payloads and run them with the intercepted data. It includes a dashboard that shows a list of issues, but should be checked for false positives.

Another is called Sequencer. It analyzes random data and then identifies weaknesses in that data to see how the values are being generated.  Decoder then allows the user to take strings and decode them using preset standards and even then encode them again.  Comparer allows you to compare the two strings and check for differences.