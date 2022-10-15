# Project REST-Rant

REST-Rant is an app where users can review restaurants.

| Method | Path | Purpose |
|---|---|---|
| GET | / | Home Page |
| GET | /places | Places index page |
| POST | /places | Create new place |
| GET | /places/new | Form page for creating a new place |
| GET | /places/:id | Details about a particular place |
| PUT | /places/:id | Update a particular place |
| GET | /places/:id/edit | Form page for editing an existing place |
| DELETE | /places/:id | Delete a particular place |
| POST | /places/:id/rant | Create a rant (comment) about a particular place |
| DELETE | /places/:id/rant/:rantid | Delete a rant (comment) about a particular place|
| GET | * | 404 page (matches any route not defined above) |

Photos:
    Photo by <a href="https://unsplash.com/@lindsaymoe?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Lindsay Moe</a> on <a href="https://unsplash.com/s/photos/noodles?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
    Photo by <a href="https://unsplash.com/@syinq?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Susan Q Yin</a> on <a href="https://unsplash.com/s/photos/coffee-cat?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
  
  