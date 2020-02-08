# Progetto Tolusso Raffaele 
Ho iniziato il progetto andando a cercare il soggetto che dovrà essere presentato, cercando modelli 3D sul web che potessero soddisfare le richieste principali della consegna. Ho trovato il modello del manico di una spada laser con tanto di textures per il rendering alla pagina https://free3d.com/it/3d-model/lightsabers-686170.html. Il modello non è né troppo semplice né troppo complesso a mio parere.
## Idea generale
L'idea è quella di presentare una spada la cui lama può essere fatta di diversi materiali tutti visualizzabili dal cliente, ad esempio una lama di "luce" come per ogni spada laser, ma anche ad esempio d'acqua.
## Sfondo
Ho trovato una cubemap coerente che rappresenta lo spazio con una luna alla pagina https://www.hiclipart.com/free-transparent-background-png-clipart-dcdwa/.
## Rendering Manico
Ho fatto il rendering del manico e impostato lo sfondo della scena con la cubemap e renderizzato il manico attraverso l'AO map e la funzione di rendering vista a lezione per superfici riflettenti utilizzando la roughness contenuta nella texture.
## Rendering "lama" 
Ho creato un semplice modello della lama usando blender e lo ho aggiunto alla scena. Ho quindi fatto gli shader per la versione della lama fatta d'acqua usando la funzione di rifrazione.