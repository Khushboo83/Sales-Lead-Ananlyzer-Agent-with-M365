# Sales Lead Analyzer – Azure AI Foundry
Custom agent in Foundry:

- Analyzes leads from text
- Custom tool for company classification
- Knowledge grounding from enterprise data
- Designed for one-click publish to M365

Shows pro-code extensibility path to Copilot ecosystem.
Estimated ROI: 60% faster lead response.

1. Testing the agent:
    - Input: "New lead: Acme Corp, 500 employees, Bangalore, pain point: slow proposal generation"
    - Expected output: Qualification score, pain points, next step, draft email.
![image.png](attachment:3ac3b8b7-f364-49be-9348-d42193ab805b:image.png)

2. Add knowledge (simulate M365 Graph data) and asking "Suggest outreach for manufacturing lead in Bangalore" → Agent uses knowledge
![image.png](attachment:15367604-0143-4883-bbfb-09e970416cd8:image.png)

Agent also gives custom outreach email
![image.png](attachment:5d75ed12-23e3-497e-87f2-bb99cc178428:image.png)
