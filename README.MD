Revolut Transaction Server
---

Prefix: /rest-api/v1/

POST    /user                       Create new user
GET     /user/<id>                  Get user by id
GET     /user/<id>/transactions     Get transactions history for selected user
                   ?q=[filter, offset, limit]

POST    /transactions/
            - from (check users existence)
            - to
            - amount (> 0)
GET     /transactions/q=[id | from | to | date]
