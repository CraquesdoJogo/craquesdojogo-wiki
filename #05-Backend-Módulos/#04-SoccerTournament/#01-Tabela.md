| Nome | Tipo | Padrão | Descrição |
|------|------|--------|-----------|
| id |  |  |  |
| name |  |  |  |
| picture |  |  |  |
| type |  |  | tipo de torneio, sistema |
| user_id |  |  | dono |
| winner|  |  | Vencedor a ser preenchido após finalização |
| winner_2|  |  | 2 colocado |
| winner_3|  |  | 3 colocado |
| date_start |  |  |  |
| date_end |  |  |  |
| player_top_scorer |  |  | Id o artilheiro |
| contact_whatsapp |  |  | |
| contact_email |  |  | |


Tabela de ligação com administradores

| Nome | Tipo | Padrão | Descrição |
|------|------|--------|-----------|
| id |  |  |  |
| soccer_tournament_id |  |  |  |
| user_id |  |  |  |


Tabela de ligação com os times

| Nome | Tipo | Padrão | Descrição |
|------|------|--------|-----------|
| id |  |  |  |
| soccer_tournament_id |  |  |  |
| team_id |  |  |  |
| count_goals |  |  |  |
| count_games |  |  |  |
| count_winners |  |  |  |