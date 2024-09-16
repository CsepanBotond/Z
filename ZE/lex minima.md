#szabály 
A *legkisebb lépés* elve. Ha két egymást követő harmóniában van közös hang, akkor azt ugyanabban a szólamban kell megtartani, a többi szólamot pedig a lehető legkisebb lépéssel tovább vezetni.
pl.
```music-abc
X:1 
L:1/4
K:C 
%%score {(S A T) B
V:S clef=treble stem=up
V:A clef=treble stem=up
V:T clef=treble stem=up
V:B clef=bass
[V:S] c B | c2 || g- g- | g2 |]
[V:A] G- G- | G2 || e d | e2 |]
[V:T] E D | E2 || c B | c2 |]
[V:B] C, G, | C,2 || C, G, | C,2 |]
s: C:I8 V I I5 V I
```
