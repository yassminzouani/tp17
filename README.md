# tp17<img width="998" height="671" alt="1" src="https://github.com/user-attachments/assets/79aa953f-fac3-4898-a466-34b4e968574a" />
JSON : Très rapide pour l’encodage et le décodage. C’est normal, car JSON est simple à traiter en JavaScript.

XML : L’encodage est déjà plus lent que JSON, mais le décodage est beaucoup plus coûteux (5.788 ms). XML est verbeux et la conversion XML → JSON → JS prend du temps.

Protobuf : L’encodage est un peu plus lent que JSON, mais le décodage reste rapide. Protobuf est optimisé pour le stockage binaire et la transmission rapide, donc efficace malgré sa structure plus complexe.
Conclusion sur les performances :

JSON est simple et rapide, mais pas très compact.

XML est verbeux et coûteux en décodage.

Protobuf est un excellent compromis pour les données binaires : plus compact que JSON et XML, décodage rapide, idéal pour les systèmes distribués.
