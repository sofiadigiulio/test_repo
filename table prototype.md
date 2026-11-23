#### Am I going Insane 
## I am supposed to know this 
**how hard** can it be

### example

| field | definition | DC equivalent | required? | value rule | example |
|---|---|---|---|---|---|
| `title` | name given to the object | title | yes | free text | Nascita di Venere |
| date | year of creation | date | yes | YYYY or YYYY-YYYY | 1482-1486 | 

### Draft for Region Table 

| field | definition | DC equivalent | value rule | example |
|---|---|---|---|---|
| `title` | name of the site | `title` | free text | Alba Fucens |
| `type` | type of site | `subject` | select choice | Parco Archeologico |
| `section` | section of the program that the site is from|  `isPartof` | select choice | sezione I |
| `author` | author of the paper | `creator` | name of person | Sofia Di Giulio |
| `riconoscimenti` | column dedicated to signalling if a site has a specific award | ?? | select choice | UNESCO |

`type` choices list: Parco Archeologico; Parco Nazionale; Castello, Palazzo, Reggia; Chiesa, Duomo, Edificio Religioso; Museo; Centro Storico.

`section` choices list: sezione I; sezione II; sezione III.

`riconoscimenti` choices list: UNESCO; nessuno. 

### Draft for Oveweview Table 

| field | definition | DC equivalent | value rule | example |
|---|---|---|---|---|
| `title` | name of the region | `title` | free text | Abruzzo |
| `state` | progress of completion/revision | ?? | select choice | in progress |

`state` choices list: non iniziato; in progress; sezione I finita; sezione II finita; sezione III finita; finita.
