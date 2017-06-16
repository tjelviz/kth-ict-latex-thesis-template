# kth-ict-latex-thesis-template
**Slutrapportmall för examensarbete på KTH ICT.**
Av: Olle Calderon ollecal(at)kth.se

## Krav:
- TeXLive
- En LaTeX-editor (jag rekommenderar TeXMaker)



## Användning:
- Ladda ned repot i sin helhet.
- "slutrapport.tex" är själva rapportens innehåll. Det är här du skriver allt.
- Lägg referenser i "referenser.bib" (BibTeX).
- Vissa inställningar kan göras under "INSTÄLLNINGAR" i "slutrapport.tex"
- För att generera PDF, kompilera "slutrapport.tex".
- För att ändra mallens utseende eller lägga till paket, ändra "header.tex".
- Generera framsida till rapporten här: https://intra.kth.se/kth-cover/. Lägg pdf-filen under /pics/. Skriv filnamnet under "INSTÄLLNINGAR"
- Lägg alla bilder under /pics/
- Studera "slutrapport.tex" och se vad resp. kommando ger för output i "slutrapport.pdf"! Det är nog det lättaste sättet att lära sig hur mallen fungerar.



## Möjliga framtida förbättringar:
- [ ] Automatisk generering av blanksidor så att kthcover-baksida hamnar på sista arkets rygg.
- [ ] Högerjusterad sidnumrering för innehållsförteckning (krockar med "fancy"?).
- [ ] Makro för tabeller.
- [ ] Exempel för tabeller, ekvationer, TikZ och CircuiTikZ.
- [ ] Lathund för hur man exporterar MATLAB-plottar till LaTeX.
- [ ] Exempel för datapresentation med SI-enheter (siunitx).