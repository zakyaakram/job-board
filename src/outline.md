job:
    -title
    -location
    -job type
    -description
    -published at
    -vacancy
    -salary
    -category
    -experince

    -apply job
    -post job

blog:
    -title
    -description
    -created_at
    -category
    -tags
    -author

    -search
    -comment
    -recent posts   

contact

home


login

relations:
-one to one [ user - profile ] ForeginKey
-many to many [ user - group]
-one to many [ user-post ]
