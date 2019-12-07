## Common issues & fixes


#### Maps installation
 * Head to the collections page either in your steam client or the web page (while logged in) and subscribe to the list.
 * After subscribing to the list, select the "+Subscribe to all" to sub to all the individual maps
 * Optionally favourite the collection to make it easier to find later.
 * With L4D2 closed, Steam should see the changes and install a workshop update, wait for it to complete.
 * Once that's done, open your game client and wait in the main menu for your client to scan and update the workshop addons (may take some time - multiple minutes for the first run, ~10-90s for smaller, incremental updates)
 * After the addons have completed loading, join the lobby or close your game for later.
 * Go grab a drink, you're done.

#### Local install location
 * Workshop maps automatically go in to "`..\steam\steamapps\common\Left 4 Dead 2\left4dead2\addons\workshop`"
 * DO NOT manually install maps in to the parent folder `..\left4dead2\addons` unless specifically instructed to (for non-workshop maps).
 * If you have any duplicate, conflicting or differently sourced copies of workshop maps in the parent `\addons` folder best to delete/move them to make life easier on yourself.

#### Installed addons missing or lobby asking you to download map
 * After a new subscribe/install allow Steam to complete any workshop Downloads _before_ starting your game client.
 * After opening your game, allow the client to scan, update and load your addons *before joining a lobby* (10-60 secs in menu).
 * Is it a new addition? Have you subbed to the collection changes? Revisit the workshop collection and check you're subscribed to all the maps (sadly has to be done manually every time...)
 * Is the map from a non-workshop source? Those go in to the "`..\left4dead2\addons`" folder directly. If you add files to the `..\addons\workshop` folder manually, they will get removed by the game when it looks for workshop updates (and sees no subscription for the stray files).

#### Addons list shows many addon conflicts?
 * Multi-part maps often conflict with themselves since they duplicate some assets or apply the exact same tweaks.
 * You can ignore warnings on maps you know you don't have duplicated in `\addons`.
 * Conflicts with other _non-map_ installed addons however should be investigated or the extra addons disabled for compatability/consistency reasons (if they're blocking you from connecting).

#### Can we play *this* map?
 * Have a campaign you want to try out, send it @shen or @indiv for inclusion in the collection and installation to the server.
 * Before recommending, first try it out yourself (Single Player, Co-op or a small VS test) to make sure its not completely broken and of a good enough quality to have in the rotation.
 * We prefer Steam Workshop hosted maps but can add other, manual sources if its not available via the workshop.