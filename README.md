# API
Appels REST, en relation avec tous les autres services

POST api/reservation/create (params: user, salleId, dateResa)
UPDATE api/reservation/update (params: user, resaId, modifs)
DELETE api/reservation/delete (params: user, resaId)
GET api/reservation/view (params: user, resaId)

POST api/salle/create (only role admin) (params: isAdmin, salleName)
DELETE api/salle/delete (only role admin) (params: isAdmin, salleId)

