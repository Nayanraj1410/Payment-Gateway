PAYMENT-GATEWAY
This project showcases how insecure client-side validation in payment gateways can be exploited to manipulate transaction parameters—specifically the amount—using Burp Suite.

⚙️ Tools & Environment
Operating System: Kali Linux

Proxy Tool: Burp Suite

Target: Paytm sandbox/test environment

Browser: Firefox/Chrome with proxy configured

🚀 Steps to Reproduce
Launch Burp Suite and configure browser proxy.

Initiate a transaction on Paytm sandbox.

Intercept the payment request using Burp Suite.

Modify the amount parameter before forwarding the request.

Observe how the manipulated amount is processed if server-side validation is weak.

🔍 Key Concepts
Intercepting HTTP requests

Parameter tampering

Client-side vs server-side validation

Ethical hacking best practices
