# dockercompose-to-MACM
Con questo progetto è possibile trasformare qualsiasi docker compose in un oggetto MACM definito in cypher query language. 
Ciò viene effettuato tramite il parser generator_cypher.py con il supporto della libreria appositamente creata macm.py. La libreria macm creata fa riferimento a sua volta alla libreria opensource networkx.py e all'interfaccia grafica gui.py appositamente creata. L'oggetto MACM è possibile ottenere eseguendo il parser e riempiendo i campi definiti nell'interfaccia grafica. A partire dall'oggetto creato è possibile effettuare la query che definisce tale oggetto su Neo4j che permetterà di implementare e di visualizzare graficamente il MACM ottenuto.
