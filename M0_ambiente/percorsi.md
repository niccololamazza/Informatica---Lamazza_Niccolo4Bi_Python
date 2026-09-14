## Esercizio 2 — Navigazione e percorsi nel terminale

  PS Z:\> cd "Z:\Documenti"
 PS Z:\Documenti> mkdir esercizio-percorsi
 PS Z:\Documenti> cd "Z:\Documenti\esercizio-percorsi"
PS Z:\Documenti\esercizio-percorsi> mkdir 


##Windows PowerShell
Copyright (C) Microsoft Corporation. Tutti i diritti riservati.
                                                                                                                        Installa la versione più recente di PowerShell per nuove funzionalità e miglioramenti. https://aka.ms/PSWindows                                                                                                                                 PS Z:\> cd "Z:\Documenti"                                                                                               PS Z:\Documenti> mkdir esercizio-percorsi


    Directory: Z:\Documenti


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        14/09/2026     11:02                esercizio-percorsi


PS Z:\Documenti> cd "Z:\Documenti\esercizio-percorsi"
PS Z:\Documenti\esercizio-percorsi> mkdir dati


    Directory: Z:\Documenti\esercizio-percorsi


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        14/09/2026     11:03                dati


PS Z:\Documenti\esercizio-percorsi> mkdir risultati


    Directory: Z:\Documenti\esercizio-percorsi


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        14/09/2026     11:03                risultati


PS Z:\Documenti\esercizio-percorsi> cd .\risultati
PS Z:\Documenti\esercizio-percorsi\risultati> Get-location

Path
----
Z:\Documenti\esercizio-percorsi\risultati


PS Z:\Documenti\esercizio-percorsi\risultati> ^C
PS Z:\Documenti\esercizio-percorsi\risultati> cd "Z:\Documenti\esercizio-percorsi\dati"
PS Z:\Documenti\esercizio-percorsi\dati> cd \risultati
cd : Impossibile trovare il percorso 'Z:\risultati' perché non esiste.
In riga:1 car:1
+ cd \risultati
+ ~~~~~~~~~~~~~
    + CategoryInfo          : ObjectNotFound: (Z:\risultati:String) [Set-Location], ItemNotFoundException
    + FullyQualifiedErrorId : PathNotFound,Microsoft.PowerShell.Commands.SetLocationCommand

PS Z:\Documenti\esercizio-percorsi\dati>
