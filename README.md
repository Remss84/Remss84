graph TD;
A[Décision de liquidation] --> B[Volontaire ou Judiciaire];
B --> C[Liquidation Volontaire];
B --> D[Liquidation Judiciaire];
C --> E[Nomination du liquidateur];
D --> E[Nomination du liquidateur];
E --> F[Inventaire des actifs et passifs];
F --> G[Réalisation de l’actif];
G --> H[Fonds suffisants pour créanciers ?];
H --> I[Oui : Paiement des créanciers];
H --> J[Non : Répartition selon priorité];
I --> K[Bilan de liquidation];
J --> K[Bilan de liquidation];
K --> L[Radiation au RCS];
L --> M[Société Dissoute];
