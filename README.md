# gargun-club-api

## Skiss DB-schema

### Tabeller

#### user

- id

tie to authorization/authentication

#### picture

- id
- uploader (user)
- uploaded (datetime)
- copyright ???
- url
- based_on (picture)
- relation [improvement, variant]

#### picture_tag

- picture
- user
- tag (string or fk?)

#### pricture_rating ???

- picture
- user
- key
- value

#### ratings ???

- rating

#### picture_comment

- picture
- user
- created
- comment
- alert
