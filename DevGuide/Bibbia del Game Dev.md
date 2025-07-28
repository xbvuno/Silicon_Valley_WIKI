In questa sezione troverete le regole da rispettare durante lo sviluppo del gioco così da non impazzire con refactoring continui e spaghetti code.

# Regola n. 1 - Organizzazione del Lavoro
Prima di iniziare a lavorare ad una funzione, chiedere sempre se qualcuno ci sta già lavorando. Così da non fare lavoro inutile. Per vedere le cose da fare esiste il sito **HacknPlan** dove sono scritte tutte le funzioni da sviluppare.

# Regola n. 2 - Version Control
Per il version control del progetto useremo il nostro grande dio GIT.
In questo caso, per evitare problemi andremo di Pull Requests. Dalla Repository principale ogni dev dovrà fare un Fork e lavorare su di essa alla sua feature, una volta completata si apre una Pull Request per aggiungerla al progetto principale.

# Regola n. 3 - Godot Style Guide
Rispettate il [Godot Style Guide](https://docs.godotengine.org/en/stable/tutorials/scripting/gdscript/gdscript_styleguide.html)

# Regola 4 - Seguite lo schema del File System
[Qui](File%20System.md) potete trovare lo schema del File System

# Regola 5 - Formattazione testo
Usare i seguenti stili di formattazione delle variabili in base al loro scopo(secondo il [Godot Style Convenction](https://docs.godotengine.org/en/4.4/tutorials/scripting/gdscript/gdscript_styleguide.html#naming-conventions)):
- 🐍🏡snake_case🐍🏡 : variabile normale
- 🏡PascalCase🏡 : nomi classi e nodi
- 🧢🔒CAPS_LOCK🧢🔒: per i nodi importati nel codice e costanti

# Regola 6 - Estendete le classi
Se dovete fare una modifica ad una classe o ad uno script cercate di estenderlo.
In questo modo ci saranno meno conflitti nel codice durante i merge e soprattutto meno errori in caso di modifiche.

# Regola 7 - NON modificate gli Addon
Se scaricate una libreria e dovete apportare una modifica, non modificatela direttamente ma create uno script e fategli ereditare la libreria ed implementate le modifiche.

# Regola 8 - Per qualsiasi dubbio chiedete
Se avete qualche dubbio riguardante il progetto oppure come fare una determinata cosa, chiedete sul discord e tutto si risolverà😎.


