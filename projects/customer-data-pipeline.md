# Event-Driven Customer Data Pipeline

I developed and maintained a Node.js backend at Zehnder’s of Frankenmuth to collect and organize real-time customer data from Oracle Cloud.

## How it worked

1. The service issued parallel API requests to retrieve customer data.
2. The pipeline processed the nested JSON returned by the APIs.
3. The backend organized the resulting records for downstream use.

**Tools** · Node.js, Oracle Cloud APIs, JSON.
