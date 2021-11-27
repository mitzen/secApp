# secApp

Key secret management operator for kubernetes

Helps with secrets management in a kubernetes cluster

- integrated with kv (azure for now) to retrieve and inject secret into cluster. 

- provide secret rotation - immediate or within a specific time 

- ability to revoke compromised password 

- provide logging to secret key modifications, update to provide high visibiliies. Alth we rotate the keys, but we need to know what's happening. 

------------------------------------------------------------


