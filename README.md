# challenge-2
Powershell script to query the meta data instance within Azure.
IMDS is a REST API that's available at a well-known, non-routable IP address (169.254.169.254). You can only access it from within the VM. 
Communication between the VM and IMDS never leaves the host.
