# Oprydningsrobotten

Tag et billede af det, der roder, og en AI-robot laver en plan med én konkret oprydningsopgave ad gangen. Du kan se hvor lang tid det tager, og krydse opgaverne af undervejs.

## Sådan ser robotten

Robotten kører gratis direkte på telefonen. Den bruger to små AI-modeller (DETR til at finde ting og CLIP til at genkende rod), som hentes første gang, ca. 130 MB, og derefter gemmes i browseren. Billedet forlader aldrig telefonen.

Valgfrit: Under "Gør robotten klogere" kan man indsætte en gratis Google-nøgle fra https://aistudio.google.com/apikey for mere præcise planer. Inde i Claude bruger robotten Claude.

## Kør siden

Slå GitHub Pages til under Settings, Pages, og vælg branch `main` og mappen `/ (root)`.
