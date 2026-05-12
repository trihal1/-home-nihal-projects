flowchart TB
    subgraph TTWO[Take-Two Interactive Software Inc.]
        direction TB
        HQ[Headquarters: New York City, NY]
        CEO[CEO: Strauss Zelnick]
        Ticker[Publicly Traded: NASDAQ - TTWO]
    end

    subgraph Shareholders[Major Institutional Shareholders]
        direction LR
        Vanguard[The Vanguard Group<br>(~11.81%)]
        BlackRock[BlackRock Inc.<br>(~10.21%)]
        Savvy[Savvy Games Group<br>(~6.16%)]
        StateStreet[State Street Corp.<br>(~6.16%)]
        Others[Other Institutions<br>(~65.66%)]
    end

    TTWO --> Rockstar
    TTWO --> 2K
    TTWO --> Zynga
    TTWO --> Ghost[Ghost Story Games]
    TTWO --> NBA_League[NBA 2K League<br>50% Joint Venture]
    
    Shareholders -.->|Ownership Stake| TTWO

    subgraph Rockstar[Rockstar Games]
        direction TB
        R_Studio[Key Studios]
        R_North[Rockstar North<br>Grand Theft Auto Series]
        R_SanDiego[Rockstar San Diego<br>Red Dead Series]
        R_Other[Rockstar Leeds, Toronto,<br>New England, London, etc.]
        R_Games[Key Franchises]
        R_GTA[Grand Theft Auto]
        R_RDR[Red Dead Redemption]
        R_MP[Max Payne]
        R_MC[Midnight Club]
        R_Bully[Bully]
        R_LAN[L.A. Noire]
    end

    subgraph 2K[2K Games Inc.]
        direction TB
        K_Labels[Publishing Sub-Labels]
        K_Games[2K Games]
        K_Sports[2K Sports]
        K_Play[2K Play]
        
        K_Studios[Key Development Studios]
        VC[Visual Concepts<br>NBA 2K, WWE 2K]
        Firaxis[Firaxis Games<br>Civilization, XCOM]
        Gearbox[Gearbox Software<br>Borderlands, Homeworld, Duke Nukem]
        Hangar13[Hangar 13<br>Mafia Series]
        Other_2K[Cloud Chamber, 31st Union,<br>Cat Daddy Games, etc.]
    end

    subgraph Zynga[Zynga Inc.]
        direction TB
        Z_Studios[Key Mobile Studios]
        Socialpoint[Socialpoint<br>Dragon City, Monster Legends]
        Playdots[Playdots<br>Dots]
        Nordeus[Nordeus<br>Top Eleven]
        GRAM[Gram Games<br>1010!, Merge Dragons!]
        Z_Games[Key Mobile Titles]
        Z_Farm[FarmVille Series]
        Z_Poker[Zynga Poker]
        Z_Words[Words with Friends]
    end