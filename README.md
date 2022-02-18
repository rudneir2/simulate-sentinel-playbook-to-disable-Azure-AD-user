# simulate-sentinel-playbook-to-disable-Azure-AD-user

## Architecture diagram (draft)

![image](https://user-images.githubusercontent.com/97529152/154761217-73d10ab7-88f4-4066-8e17-9ae669f9dc12.png)

## step by step 

1. through Microsoft Sentinel left menu, go to "Automation", "playbook template" and then choose and build the playbook called "Block AAD user - Incident"
2. it is required that you understand how to create or edit Azure Logic Apps (out of scope of this repo)
3. make sure the Playbook (Logic App) is built and running properly
4. attach the playbook to a specific Analytic Query at Microsoft Sentinel
5. Simulate a user anonymous access according to the instructions from this link below:
https://docs.microsoft.com/en-us/azure/active-directory/identity-protection/howto-identity-protection-simulate-risk#anonymous-ip-address
