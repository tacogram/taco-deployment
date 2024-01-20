# Taco Deployment

Docker deployment for Taco web server

Contents:

- `Taco` web API server and web application
- `PostgreSQL` database
- `pgAdmin` (optional)

## Running

```sh
docker-compose up -d
```

Navigate to <http://127.0.0.1:8080>.

Default account:

- username: `denys.vuika@taco.app`
- password: `password`

### Demo Accounts

| Username                    | Password |
|-----------------------------|----------|
| denys.vuika@taco.app        | password |
| admin@taco.app              | password |
| Imaad.Casey@taco.app        | password |
| Jordyn.Frank@taco.app       | password |
| Marwan.Combs@taco.app       | password |
| Philip.Rhodes@taco.app      | password |
| Chardonnay.Raymond@taco.app | password |
| Akram.Farmer@taco.app       | password |
| Nichola.Mackie@taco.app     | password |
| Ines.Page@taco.app          | password |
| Ephraim.Gonzalez@taco.app   | password |
| Tyrell.Stark@taco.app       | password |
| Tasha.Whitmore@taco.app     | password |
| Hawwa.Davenport@taco.app    | password |

## Updating containers

```sh
docker-compose pull
```

## Cleanup

```sh
docker-compose down
```
