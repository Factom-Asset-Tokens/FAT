sequenceDiagram

    Client->>Light Node: HTTP/WS
    Light Node-->>Client: HTTP/WS
    
    Client->>Medium Node: HTTP/WS
    Medium Node-->>Client: HTTP/WS
    
    Light Node->>Medium Node: HTTP/WS
    Medium Node-->>Light Node: HTTP/WS
    
    Medium Node->>Factom: HTTP
    Factom-->>Medium Node: HTTP
     Factom-->>Medium Node: Pending Entries
    
    Note right of Client: Alternatively send/get transactions directly
    Client->>Factom: HTTP
    Factom-->>Client: HTTP