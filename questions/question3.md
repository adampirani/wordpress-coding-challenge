### Consider the following scenario:

#### For all players in the NBA so far:

* A `player` custom post type exists with a meta field called `player_external_id`
  * Assume all players have a unique value in this field (different than the WordPress post ID)
  
#### For the upcoming season, all players will have a page on a 3rd party site with the following URL structure:

`http://www.nba-player-tv.com/channel/{player_external_id}`

* A new meta field `player_tv_url` was added to the `player` custom post
* All new players drafted for the upcoming season have the proper value set

#### Summary

| Type | Name |
| ---- | ---- |
| Custom Post Type | player |
| Custom Fields | player_external_id, player_tv_url |

### We need to update any missing `player_tv_url` post metadata

1. Write the code that would accomplish this.
1. How would you trigger the execution of this code?


