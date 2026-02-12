# Plotter Opt

Software scritto in Processing (Java) che utilizza la libreria Geomerative per generare G-code da immagini SVG per un plotter.

## Funzionalità

- Legge un file SVG e trova le forme (parsing tramite Geomerative).
- Effettua l'hatching (riempimento a tratteggio) delle forme mediante linee parallele.
- Crea un file G-code da inviare al plotter per dipingere l'immagine.
- Ottimizza la direzione delle righe di hatching per ridurre gli spostamenti a vuoto.
- Include una vista interattiva per ispezionare forme e righe di hatching a fine elaborazione (tasti 1/2/3/4/9).

## Librerie

- **Geomerative**: Utilizzata per il parsing SVG, creazione RShape e gestione geometria 2D (hatching, segmenti, ecc.).

## Output

Le cartelle di output `GCODE/` sono generate durante l'esecuzione e sono escluse dal repository Git.
