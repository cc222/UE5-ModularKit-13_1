# PLAN MODULOW - CYBERPUNK (UE5-ModularKit-13_1)

## Styl: underground slumsy 

**SIATKA**
- Podstawowy snapping: 1 m (detale 0.5 m, propsy 0.1 m)
- Szerokosc modulu: 4 m (wersja waska 2 m)
- Wysokosc pietra: 4 m
- Wysokosc parteru: 5 m

**MODULY**
 1. Sciana pelna (tynk/beton)          4 x 4 m      ref: m_ref3, m_ref12, sref3
 2. Sciana z oknem                     4 x 4 m      ref: m_ref8, cref9, sref12
 3. Sciana waska                       2 x 4 m      ref: cref4, m_ref11
 4. Naroznik zewnetrzny                wys. 4 m     ref: m_ref10, m_ref6
 5. Parter z witryna sklepu            4 x 5 m      ref: m_ref4, m_ref10, sref9
 6. Parter z wejsciem i roleta         4 x 5 m      ref: m_ref3, m_ref7
 7. Gzyms / listwa miedzypietrowa      4 x 0.5 m    ref: m_ref6, cref9
 8. Attyka / krawedz dachu             4 x 1 m      ref: cref6, cref12
 9. Balkon z barierka                  4 x 1.5 m    ref: m_ref9, m_ref10, m_ref12
10. Schody pozarowe (segment)          4 x 4 m      ref: m_ref2, sref8
11. Markiza nad sklepem                4 x 1 m      ref: m_ref7, m_ref8, cref4
12. Szyld neonowy (pionowy/poziomy)    1x3 / 2x1 m  ref: cref11, m_ref4, m_ref8
13. Klimatyzator                       ok. 1 x 0.5 x 0.5 m   ref: m_ref3, m_ref9, sref9
14. Krata / klatka okienna             2 x 2 m      ref: m_ref3, m_ref12
15. Rury i kable (prosty, kolano, uchwyt)  2 m      ref: m_ref11, m_ref12, sref3
16. Dach: zbiornik wody + antena       ok. 2 x 2 m  ref: cref3, sref6

**MATERIALY**
Brudny beton/tynk, cegla, metal malowany z rdza, szklo,
emissive (neony), plastik (obudowy klimatyzatorow).

**PODZIAL PRACY**
***cc222***       (sciany):            1, 2, 3, 4, 13
***sk0l0pendra*** (parter i neony):    5, 6, 11, 12, 15
***s35705***      (pietra i dach):     7, 8, 9, 10, 14, 16