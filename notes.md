## Precisazioni 

- Nella categoria "emission" (es. Euro 5) ho scelto CHAR(7), considerando un carattere in più per sicurezza. 

- Nella categoria "license_plate" ho usato VARCHAR perchè ho pensato di includere non solo macchine con targhe italiane, ma anche estere. Nel caso delle targhe unicamente italiane avrei scelto CHAR(7), essendo costituite sempre da 7 caratteri.

- Ho utilizzato VARCHAR(255) in alcuni campi della tabella per non incorrere nel rischio di non avere abbastanza spazio disponibie per i caratteri inseriti.