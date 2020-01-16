# Pokedex API

- Spin up a restful API server in the language of your choice

- Tasks (using the CSV file provided in this directory)

    1. Define and implement an API endpoint which returns a list of all the
       Pokemon

        ```
        // GET /pokemon/
        [
          {
            "id": 1,
            "name": "Bulbasaur",
          },
          ... // All of the rest of the rows in the CSV
        ]
        ```

    2. Define and implement an API endpoint for each Pokemon that returns
       detailed information about that Pokemon.

        ```
        // GET /pokemon/1/ returns:
        {
          "id": 1,
          "name": "Bulbasaur",
          "types": ["Grass", "Poison"],
          "total": 318,
          ... // All of the rest of the columns in the CSV
        }
        ```

    3. Implement pagination and search on the list API endpoint which returns
       all pokemon

    4. Stretch goals:
        - Caching
        - Tests
        - Ordering the results of the list endpoint
