MATCH (a:Persona)-[:AMIGO_DE*2]->(b:Persona)
WHERE a <> b
RETURN a.nombre, b.nombre
