# Extra Instructions

Rules the LLM follows when it writes SQL for `listings`.

- `price` is the nightly price in U.S. dollars. When the user asks what something costs, use `price` and round money to whole dollars in the answer.

- `host_is_superhost` and `instant_bookable` are text values `'t'` and `'f'`, not Boolean values. Use `'t'` for yes/true and `'f'` for no/false.

- When filtering by `city`, match the city name exactly as it appears in the data: `Chicago`, `Columbus`, or `Twin Cities`.

- When searching the `name` column for a listing name or keyword, use a case-insensitive search.