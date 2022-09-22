# LibreXFS

LibreXFS is a community open source project to develop and support open and free eXtensions for Financial Services with priority on Linux support.

## Key objectives

1. Maintain a collection of native device libraries
2. Provide client code examples
3. Develop and maintain reference services based on native device libraries

```mermaid
flowchart LR
  C[Client] --> D[DBus]
  D --> S[Service]
  S --> PPN[Printer Library]
  S --> SSR[Sensor Library]
  S --> OTH[Some other library]
  PPN --> Printer
  SSR --> Sensor
  OTH --> OD[Other device]
```
