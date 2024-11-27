# Graphical Abstract

## Impact of Resource & Energy Productivity on Waste Management

```mermaid
graph LR
    %% Title
    title[Impact of Resource & Energy Productivity<br>on Waste Management]

    %% Inputs
    RP[Resource Productivity]
    EP[Energy Productivity]

    %% Outcomes
    WG[Waste Generation]
    WT[Waste Treatment]

    %% Arrows with Negative Impact
    RP -- Negative Impact --> WG
    RP -- Negative Impact --> WT
    EP -- Negative Impact --> WG
    EP -- Negative Impact --> WT

    %% Styling
    classDef titleStyle fill:#f9f,stroke:#333,stroke-width:2px;
    classDef inputStyle fill:#add8e6,stroke:#333,stroke-width:1px;
    classDef outcomeStyle fill:#90ee90,stroke:#333,stroke-width:1px;
    linkStyle 0,1,2,3 stroke:#ff0000,stroke-width:2px,stroke-dasharray: 5 5;

    class title titleStyle;
    class RP,EP inputStyle;
    class WG,WT outcomeStyle;
