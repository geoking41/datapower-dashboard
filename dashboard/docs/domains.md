### Domains

A structure of a domain in datapower

```mermaid
graph LR
    A[Domain] --> B[Services]
    A --> C[Policies]
    A --> D[Configuration Objects]
    A --> E[Logging and Monitoring]
    A --> F[Data Sources]
    A --> G[Cache]
    
    B --> B1[Web Service Proxy]
    B --> B2[Multi-Protocol Gateway]
    B --> B3[XML Firewall]
    B --> B4[API Gateway]
    
    C --> C1[Security Policies]
    C --> C2[Routing Policies]
    C --> C3[Transformation Policies]
    
    D --> D1[Certificates]
    D --> D2[User Accounts]
    D --> D3[Network Settings]
    
    E --> E1[Log Targets]
    E --> E2[SNMP]
    E --> E3[Statistics]
    
    F --> F1[XML Manager]
    F --> F2[SQL Data Source]
    F --> F3[MQ Queue Manager]
    
    G --> G1[Document Cache]
    G --> G2[Result Cache]
```