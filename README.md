# Team-14
Finding the real- ip address of a cyber criminal behind a proxy or a vpn. 

In this project we are trying to find the cyber criminal's real IP address using a bait ,thus by using a malicious excel file using a  canary token.Here we host our webpage that contains the  malicious file in the ngrock server which can be accessed anywhere.The index file is hosted in ngrok. 
whenever a cyber criminal opens the the canary token,the canary token dashboard get the a request from the malicious file which ultimately leads to the real-IP address.Once the resource has been accessed, an alert is triggered notifying the object owner.

Thus By using a canary token we can find the exact ip address of the cyber criminal and access his location and internet service provider .

Even though the Tor browser uses proxy servers to dynamically update the ip address,the canary token helps us to grab the ip-address of the cyber criminal using free net, thus the original location can be known

Future Scope:-
> Knowing the hackers location can be used to avoid further attacks.
> cyber criminal cab be traced and caught.
>further details can be used for cyber-forensics.