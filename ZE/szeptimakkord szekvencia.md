#szabály #összhangzattan 
Ha egy [[teljes szeptimakkord]]ot egy másik szeptimakkord követ, akkor az utóbbit hiányosra szerkesztjük. Hiányos szeptimakkordot újból teljes követ. Ez a szabály más fűzési szabályokat felülír.

Vegyük az alábbi példát:
```music-abc
X:1 
L:2/4
M:2/4
%%score {(SAT) B}
K:C 
V:SAT
[GBe-] [FAe]
V:B clef=bass
"_I7\nT" C, "_IV7\nh" F,
```
A fenti teljes szeptimakkord 2 szeptimhangot tartalmaz: a sajátját és a következő szeptimakkordét. Az $I^7$ szeptimhangja *h*, sóhajmotívum-szerűen, lefelé oldódik *a*-ra. Az *e* előkészített szeptimhang a következő akkordban, így azt azonos szólamban megtartjuk. A [[tenor]] *g*-je *c*-re nem léphet, hiszen felfelé nincs helye, lefelé pedig átmennénk [[négyszólamú szerkesztés#Tág szerkesztés|tág szerkesztésbe]]. Így a következő szeptimakkord nem lehet teljes.