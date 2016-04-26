# League of Legends' API for Postman

This is a Postman request collection that can be parameterized for all of League of Legends' API methods. The full API reference can be found on the [Riot Games API](https://developer.riotgames.com/api/methods) page.

### Environment variables [(how-to)](https://www.getpostman.com/docs/environments) :


`baseurl` : represents the url which is going to be queried.
            By default, this value shoud be __api.pvp.net__.

`region` :  region where to retrieve data.
            It may be one of following values: __br, eune, euw, jp, kr, lan, las, na, oce, ru, tr__.
            These values were taken in [Riot's API documentation](https://developer.riotgames.com/api/methods).

`apikey` :  is your private key to access Riot's API.


#### The following endpoint categories are available :
* champion-v1.2
* championmastery
* current-game-v1.0
* featured-games-v1.0
* game-v1.3
* league-v2.5
* lol-static-data-v1.2
* lol-status-v1.0
* match-v2.2
* matchlist-v2.2
* stats-v1.3
* summoner-v1.4
* team-v2.4
