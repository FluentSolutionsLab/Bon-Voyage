# Requirements (v1)

Actors: `Customer`, `Traveller`, `Travel Agent`, `System Admin`

- A `Customer` can search for trips they're interested in
- A `Customer` can book tickets for the trips they're interested in
- A `Customer` must be registered to book tickets
- A `Customer` can book as many tickets as available, provided each ticket is assigned to an identified `Traveller`
- After booking tickets, a `Customer` gets notified by email with ticket details
- `Travel Agents` must log on to perform any action on the system
- A `Travel Agent` adds trips, specifying the number of available places/tickets (1 place = 1 ticket)
- A `System Admin` manages `Travel Agents` accounts
- A `System Admin` and a `Travel Agent` can see the list of `Travellers` on each trip
