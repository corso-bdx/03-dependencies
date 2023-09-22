Dependencies
============

Copiare le classi dell'esercizio precedente "Calculator" in un
nuovo progetto di tipo "libreria di classi" in questa solution.

Scrivere un programma che legge il file YAML "data.yml" ed utilizza
le classi di "Calculator" per eseguire l'operazione indicata nel file.

Note:
- Il nome del file da leggere deve essere passato come parametro da linea di comando
- Usare il pacchetto NuGet "YamlDotNet" per leggere i file YAML
- Gestire errori di configurazione (figura non valida, operazione non valida)

## Esercizio bonus

Se il programma rileva che il file ha estensione ".toml", deve interpretarlo
come file TOML piuttosto che YAML.

Note:
- Usare il pacchetto NuGet "Tomlyn" per leggere i file TOML
