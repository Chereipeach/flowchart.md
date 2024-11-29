
   ```mermaid
   flowchart TD
   
    A[Wet Waste<br>🍎🥬 Food Scraps] -->|Organic Waste| R[Recycling Center<br>♻️]
    A --> E[Waste-to-Energy Plant<br>⚡]
    
    B[Dry Waste<br>📄🥤 Paper, Plastic, Metal] -->|Recyclables| R
    B --> E
    
    C[Hazardous Waste<br>🔋🧪 Chemicals, Batteries] -->|Specialized Treatment| R
    C --> E
    
    classDef wetWaste fill:#66c2a5,stroke:#000,color:#000;
    classDef dryWaste fill:#fc8d62,stroke:#000,color:#000;
    classDef hazardousWaste fill:#8da0cb,stroke:#000,color:#000;
    classDef processingCenter fill:#e78ac3,stroke:#000,color:#000;
    
    class A wetWaste;
    class B dryWaste;
    class C hazardousWaste;
    class R,E processingCenter;
