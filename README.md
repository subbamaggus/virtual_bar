# virtual_bar

ich geh an den kuehlschrank 
ich geh in die kneipe
    kneipe anlegen
        gps
        name
        geschlossene gesellschaft
        
mitteilen:
ich nehme ein getraenk
    allen in der kneipe (default kneipe) 
    allen (default kuehlschrank)
leer getrunken

jemanden in die kneipe einladen
eine kneipe verlassen
schloofe gehe (alle nachrichten aus heute)


zwei kneipen zusammenlegen




getraenk hinzufuegen

aufenhaltsort:

bett (N/A) <> zuhause <> kneipe


@startuml
hide empty description

[*] --> zuhause
zuhause --> [*]

zuhause --> trinken
zuhause --> kneipe

trinken --> zuhause

trinken --> kneipe

kneipe --> zuhause
kneipe --> trinken

@enduml
