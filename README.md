# Player Tournament

A PHP project that simulates a tournament between players and determines a winner based on skill level
and luck.

## Object model

- **Jugador (Player)**: a player with a name, skill level and luck attributes.
- **Enfrentamiento (Matchup)**: a matchup between two players that determines a winner.
- **Torneo (Tournament)**: the tournament itself — holds the set of players and the logic to simulate
  the tournament and determine the overall winner.

## Tests

Unit tests written with PHPUnit verify the tournament simulation and confirm the winner is a `Jugador`
instance present in the provided player list.

## API

Includes a small API (`api/`) documented with Swagger (`swagger.json` / `swagger-ui-dist`).

## Documentation

Detailed explanations of classes and methods live in the source code comments.

## Requirements

- PHP 8+
- Composer

## Running the tests

```bash
composer install
vendor/bin/phpunit
```
