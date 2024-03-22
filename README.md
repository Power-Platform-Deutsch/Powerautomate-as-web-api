# Powerautomate-as-web-api
Using Powerautomate to simulate a web api which than can be consumed as a customer connector in PowerApps - demo to learn about WebApi and Custom Connectors without the need to learn about a connector

Trigger: When an HTTO request is received

Action - Response

![image](https://github.com/Power-Platform-Deutsch/Powerautomate-as-web-api/assets/2076412/5c836f1d-39df-40ac-accc-6549bc14921d)

Security

URL Logik:

Wenn ANYONE gewählt ist, wird eine URL mit SAS Token bereitgestellt:

https://prod-33.westus.logic.azure.com:443/workflows/ea5cd024961248568b21a8c7bd6bb1ae/triggers/manual/paths/invoke?api-version=2016-06-01&sp=%2Ftriggers%2Fmanual%2Frun&sv=1.0&sig=FROM-SYSTEM-GENERATED-SECURITY-TOKEN

sig=FROM-SYSTEM-GENERATED-SECURITY-TOKEN

Wäre hier das Token

https://www.linkedin.com/pulse/securing-http-triggered-flow-power-automate-abd-elmonem-elsherbeny/



