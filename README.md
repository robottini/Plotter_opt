# Plotter Opt

Software scritto in Processing (Java) che utilizza la libreria Geomerative per generare G-code da immagini SVG per un plotter.

## Funzionalità

- Legge un file SVG e trova le forme (parsing tramite Geomerative).
- Effettua l'hatching (riempimento a tratteggio) delle forme mediante linee parallele.
- Crea un file G-code da inviare al plotter per dipingere l'immagine.

## Librerie

- **Geomerative**: Utilizzata per il parsing SVG, creazione RShape e gestione geometria 2D (hatching, segmenti, ecc.).
