
## Lineární příběh

@startuml
skin rose

start
:Hrdina se vydává na cestu;
:Potkává draka;
:Boj s drakem;
:Porazit draka;
:Vrátit se domů s pokladem;
stop
@enduml

## Rozvětvený příběh

@startuml
skin rose

start
:Hrdina se vydává na cestu;
if (Rozhodnout se bojovat s drakem?) then (Ano)
 :Boj s drakem;
 if (Porazit draka?) then (Ano)
    :Porazit draka;
    :Vrátit se domů s pokladem;
 else (Ne)
    :Uprchnout;
 endif
else (Ne)
 :Uprchnout;
endif
stop
@enduml
