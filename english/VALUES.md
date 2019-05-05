

-------
## ABSOLUTE VALUE:
The absolute value of the specified value.
 - `    VALUE`:The real number value whose absolute value will be computed.


-------
## ADD:
The sum of two numbers or vectors.
 - `    VALUE`:The left-hand operand. May be any value that results in a number or a vector.
 - `    VALUE`:The right-hand operand. May be any value that results in a number or a vector.


-------
## ALL DEAD PLAYERS:
An array containing all dead players on a team or in the match.
 - `    TEAM`:The team or teams from which players may come.


-------
## ALL HEROES:
The array of all heroes in overwatch.


-------
## ALL LIVING PLAYERS:
An array containing all living players on a team or in the match.
 - `    TEAM`:The team or teams from which players may come.


-------
## ALL PLAYERS:
An array containing all players on a team or in the match.
 - `    TEAM`:The team or teams from which players may come.


-------
## ALL PLAYERS NOT ON OBJECTIVE:
An array containing all players occupying neither a payload nor a control point (either on a team or in the match).
 - `    TEAM`:The team or teams from which players may come.


-------
## ALL PLAYERS ON OBJECTIVE:
An array containing all players occupying a payload or control point (either on a team or in the match).
 - `    TEAM`:The team or teams from which players may come.


-------
## ALLOWED HEROES:
The array of heroes from which the specified player is currently allowed to select.
 - `    PLAYER`:The player whose auowed heroes to acquire.


-------
## ALTITUDE OF:
The player's current height in meters above a surface. Results in o whenever the player is on a surface.
 - `    PLAYER`:The player whose altitude to acquire.


-------
## AND:
Whether both of the two inputs are true (or equivalent to true).
 - `    VALUE`:One of the two inputs considered. If both are true (or equivalent to true), then the and value is true.
 - `     TRUE), THEN THE AND VALUE IS TRU`:One of the two inputs considered. If both are true (or equivalent to true), then the and value is true.


-------
## ANGLE DIFFERENCE:
The difference in degrees between two angles. After the angles are wrapped to be within +/- 180 of each other, the result is positive if the second angle is greater than the first angle. Otherwise, the result is zero or negative.
 - `    ANGLE`:One of the two angles between which to measure the resulting anole.
 - `    ANGLE`:One of the two angles between which to measure the resulting anole.


-------
## APPEND TO ARRAY:
A copy of an array with one or more values appended to the end.
 - `    ARRAY`:The array to which to append.
 - `    VALUE`:The value to append to the end of the array. If this value is itself an array. Each element is appended.


-------
## ARRAY SLICE:
A copy of the specified array containing only values from a specified index range.
 - `    ARRAY`:The array from which to make a copy.
 - `    START INDEX`:The first index of the range.
 - `    COUNT`:The number of elements in "-ie resulting array. The resulting array wu contain fewer elements if the specified range exceeds the bounds of the array.


-------
## ATTACKER:
The player that dealt the damage for the event currently being processed by this rule. May be the same as the victim or the event player.


-------
## CLOSEST PLAYER TO:
The player closest to a position, optionally restricted by team.
 - `    CENTER`:The position from which to measure proximity.
 - `    TEAM`:The team or teams from which the closest player will come.


-------
## COMPARE:
Whether the comparison of the two inputs is true.
 - `    VALUE`:The left-hand side of the comparison. This may be any value type if the operation is or i-. Otherwise, real numbers are expected.
 - `    VALUE`:The right-hand side of the comparison. This may be any value type if the operation is or i-. Otherwise, real numbers are expected.


-------
## CONTROL MODE SCORING PERCENTAGE:
The score percentage for the specified team in control mode.
 - `    TEAM`:The team whose score percentage to acquire.


-------
## CONTROL MODE SCORING TEAM:
The team that is currently accumulating score percentage in control mode. Results in all if neither team is accumulating score.


-------
## COSINE FROM DEGREES:
Cosine of the specified angle in degrees.
 - `    ANGLE`:Angle in degrees.


-------
## COSINE FROM RADIANS:
Cosine of the specified angle in radians.
 - `    ANGLE`:Angle in radians.


-------
## COUNT OF:
The number of elements in the specified array.
 - `    ARRAY`:The array whose elements will be counted.


-------
## CROSS PRODUCT:
The cross product of the specified values. (left cross up equals forward.)
 - `    VALUE`:The left-hannide vector operand of the cross product.
 - `    VALUE`:The right-hand-side vector operand of the cross product.


-------
## CURRENT ARRAY ELEMENT:
The current array element being considered. Only meaningful during the evaluation of values such as filtered array and sorted array.


-------
## DIRECTION FROM ANGLES:
The unit-length direction vector corresponding to the specified angles.
 - `    HORIZONTAL ANGLE`:The horizontal angle in degrees used to construct the resulting vector.
 - `    VE RTICAL ANGLE`:The vertical angle in degrees used to construct the resulting vector.


-------
## DIRECTION TOWARDS:
The unit-length direction vector from one position to another.
 - `    START POS`:The position from which the resulting direction vector wu point.
 - `    END P05`:The position to which the resulting direction vector will point.


-------
## DISTANCE BETWEEN:
The distance between two positions in meters.
 - `    START POS`:One of the two positions used in the distance measurement.
 - `    END P05`:One of the two positions used in the distance measurement.


-------
## DIVIDE:
The ratio of two numbers or vectors. A vector divided by a number will yield a scaled vector. Division by zero results in zero.
 - `    VALUE`:The left-hand operand. May be any value that results in a number or a vector.
 - `    VALUE`:The right-hand operand. May be any value that results in a number or a vector.


-------
## DOT PRODUCT:
The dot product of the specified values.
 - `    VALUE`:One of mo vector operands of the dot product.
 - `    VALUE`:One of mo vector operands of the dot product.


-------
## DOWN:
Shorthand for the directional vector(o, -1 , 0), which points downward.


-------
## EMPTY ARRAY:
An array with no elements.


-------
## ENTITY EXISTS:
Whether the specified player, icon entity, or effect entity still exists. Useful for determining if a player has left the match or an entity has been destroyed.
 - `    ENTITY`:The player. Icon entity, or effect entity whose existence to check.


-------
## EVENT DAMAGE:
The amount of damage received by the victim for the event currently being processed by this rule.


-------
## EVENT PLAYER:
The player executing this rule, as specified by the event. May be the same as the attacker or victim.


-------
## EVENT WAS CRITICAL HIT:
Whether the damage was a critical hit (such as a headshot) for the event currently being processed by this rule.


-------
## EYE POSITION:
The position of a player's first person view (used for aiming)
 - `    PLAYER`:The position of a player's first person view (used for aiming)


-------
## FACING DIRECTION OF:
The unit-length directional vector of a player's current facing relative to the world. This value includes both horizontal and vertical facing.
 - `    PLAYER`:The player whose facing direction to acquire.


-------
## FALSE:
The boolean value of false.


-------
## FARTHEST PLAYER FROM:
The player farthest from a position, optionally restricted by team.
 - `    CENTER`:The position from which to measure distance.
 - `    TEAM`:The team or teams from which the farthest player will come.


-------
## FILTERED ARRAY:
A copy of the specified array with any values that do not match the specified condition removed.
 - `    ARRAY`:The array whose copy will be filtered.
 - `    CONDITION`:The condition that is evaluated for each element of the copied array. If the condition is true, the element is kept in the copied array. Use the current array element value to reference the element of the array currently being considered.


-------
## FIRST OF:
The value at the start of the specified array. Results in o if the specified array is empty.
 - `    ARRAY`:The array from which the value is acquired.


-------
## FLAG POSITION:
The position of a specific team's flag in capture the flag.
 - `    TEAM`:The team whose flag position to acquire.


-------
## FORWARD:
Shorthand for the directional vector(o, o, l), which points forward.


-------
## GLOBAL VARIABLE:
The current value of a global variable, which is a variable that belongs to the game itself.
 - `    VARIABLE`:The variable whose value to acquire.


-------
## HAS SPAWNED:
Whether an entity has spawned in the world. Results in false for players who have not chosen a hero yet.
 - `    ENTITY`:The player. Icon entity, or effect entity whose presence in world to check.


-------
## HAS STATUS:
Whether the specified player has the specified status, either from the set status action or from a non-scripted game mechanic.
 - `    PLAYER`:The player whose status to check.
 - `    STATUS`:The status to check for.


-------
## HEALTH:
The current health of a player, including armor and shields.
 - `    PLAYER`:The player whose health to acquire.


-------
## HEALTH PERCENT:
The current health of a player as a percentage of their max health, including armor and shields.
 - `    PLAYER`:The player whose health percentage to acquire.


-------
## HERO:
A hero constant.
 - `    HERO`:A hero constant.


-------
## HERO ICON STRING:
Converts a hero parameter into a string that shows up as an icon.
 - `    VALUE`:The hero that will be converted to an icon.


-------
## HERO OF:
The current hero of a player.
 - `    PLAYER`:The player whose hero ro acquire.


-------
## HORIZONTAL ANGLE FROM DIRECTION:
The horizontal angle in degrees corresponding to the specified direction vector.
 - `    DIRECTION`:The direction vector from which to acquire a horizontal angle in degrees. The vector is unitized before calculation begins.


-------
## HORIZONTAL ANGLE TOWARDS:
The horizontal angle in degrees from a player's current forward direction to the specified position. The result is positive if the position is on the player's left. Otherwise, the result is zero or negative.
 - `    PLAYER`:The player from whose current facing the angle begins.
 - `    POSITION`:The position in the world where the angle ends.


-------
## HORIZONTAL FACING ANGLE OF:
The horizontal angle in degrees of a player's current facing relative to the world. This value increases as the player rotates to the left (wrapping around at +/- 1 80).
 - `    PLAYER`:The player whose horizontal facing angle to acquire.


-------
## HORIZONTAL SPEED OF:
The current horizontal speed of a player in meters per second. This measurement excludes all vertical motion.
 - `    PLAYER`:The player whose horizontal speed to acquire.


-------
## INDEX OF ARRAY VALUE:
The index of a value within an array or -1 if no such value can be found.
 - `    ARRAY`:The array in which to search for the specified value.
 - `    VALUE`:The value for which to search.


-------
## IS ALIVE:
Whether a player is alive.
 - `    PLAYER`:The player whose life to check.


-------
## IS ASSEMBLING HEROES:
Whether the match is currently in its assemble heroes phase.


-------
## IS BETWEEN ROUNDS:
Whether the match is between rounds.


-------
## IS BUTTON HELD:
Whether a player is holding a specific button.
 - `    PLAYER`:The player whose button to check.
 - `    BUTI'ON`:The button to check.


-------
## IS COMMUNICATING:
Whether a player is using a specific communication type (such as emoting, using a voice line, etc. ).
 - `    PLAYER`:The player whose communication status to check.
 - `    TYPE`:The type of communication to consider. The duration of emotes is exact. The duration of voice lines is assumed to be 4 seconds. And all other durations are assumed to be 2 seconds.


-------
## IS COMMUNICATING ANY:
Whether a player is using any communication type (such as emoting, using a voice line, etc. ).
 - `    PLAYER`:The player whose communication status to check.


-------
## IS COMMUNICATING ANY EMOTE:
Whether a player is using an emote.
 - `    PLAYER`:The player whose emoting status to check.


-------
## IS COMMUNICATING ANY VOICE LINE:
Whether a player is using a voice line. (the duration of voice lines is assumed to be 4 seconds.)
 - `    PLAYER`:The player whose voice line status to check.


-------
## IS CONTROL MODE POINT LOCKED:
Whether the point is locked in control mode.


-------
## IS CROUCHING:
Whether a player is crouching.
 - `    PLAYER`:The player whose crouching status to check.


-------
## IS CTF MODE IN SUDDEN DEATH:
Whether the current game of capture the flag is in sudden death.


-------
## IS DEAD:
Whether a player is dead.
 - `    PLAYER`:The player whose death to check.


-------
## IS FIRING PRIMARY:
Whether the specified player's primary weapon attack is being used.
 - `    PLAYER`:The player whose primary weapon attack usage to check.


-------
## IS FIRING SECONDARY:
Whether the specified player's secondary weapon attack is being used.
 - `    PLAYER`:The player whose secondary weapon attack usage to check.


-------
## IS FLAG AT BASE:
Whether a specific team's flag is at its base in capture the flag.
 - `    TEAM`:The team whose flag to check.


-------
## IS FLAG BEING CARRIED:
Whether a specific team's flag is being carried by a member of the opposing team in capture the flag.
 - `    TEAM`:The team whose flag to check.


-------
## IS GAME IN PROGRESS:
Whether the main phase of the match is in progress (during which time combat and scoring are allowed).


-------
## IS HERO BEING PLAYED:
Whether a specific hero is being played (either on a team or in the match).
 - `    HERO`:The hero to check for play.
 - `    TEAM`:The team or teams on which to check for the hero being played.


-------
## IS IN AIR:
Whether a player is airborne.
 - `    PLAYER`:The player whose airborne status to check.


-------
## IS IN LINE OF SIGHT:
Whether two positions have line of sight with each other.
 - `    START POS`:The start position for the lineof-sight check. If a player is provided, a position 2 meters above the player's feet is used.
 - `    END P05`:The end position for the line-of-sight check. If a player is provided. A position 2 meters above the player's feet is used.


-------
## IS IN SETUP:
Whether the match is currently in its setup phase.


-------
## IS IN SPAWN ROOM:
Whether a specific player is in the spawn room (and is thus being healed and able to change heroes).
 - `    PLAYER`:The player whose spawn room status to check.


-------
## IS IN VIEW ANGLE:
Whether a location is within view of a player.
 - `    PLAYER`:The player whose view to use for n-le check.
 - `    LOCAIION`:The location to test if it's within view.
 - `    VIEW ANGLE`:The view angle to compare against in degrees.


-------
## IS MATCH COMPLETE:
Whether the match has finished.


-------
## IS MOVING:
Whether a player is moving (defined as having a nonzero current speed).
 - `    PLAYER`:The player whose moving status to check.


-------
## IS OBJECTIVE COMPLETE:
Whether the specified objective has been completed. Results in false if the game mode is not assault, escort, or assault/escort.
 - `    NUMBER`:The index of the objective to consider. Starting at o and counting up. Each control point. Payload checkpoint, and payload destination has its own index.


-------
## IS ON GROUND:
Whether a player is on the ground (or other walkable surface).
 - `    PLAYER`:The player whose ground status to check.


-------
## IS ON OBJECTIVE:
Whether a specific player is currently occupying a payload or capture point.
 - `    PLAYER`:The player whose objective status to check.


-------
## IS ON WALL:
Whether a player is on a wall (climbing or riding).
 - `    PLAYER`:The player whose wall status to check.


-------
## IS PORTRAIT ON FIRE:
Whether a specific player's portrait is on fire.
 - `    PLAYER`:The player whose portrait to check.


-------
## IS STANDING:
Whether a player is standing (defined as both not moving and not in the air).
 - `    PLAYER`:The player whose standing status to check.


-------
## IS TEAM ON DEFENSE:
Whether the specified team is currently on defense. Results in false if the game mode is not assault, escort, or assault/escort.
 - `    TEAM`:The team whose role to check.


-------
## IS TEAM ON OFFENSE:
Whether the specified team is currently on offense. Results in false if the game mode is not assault, escort, or assault/escort.
 - `    TEAM`:The team whose role to check.


-------
## IS TRUE FOR ALL:
Whether the specified condition evaluates to true for every value in the specified array.
 - `    ARRAY`:The array whose values will be considered.
 - `    CONDITION`:The condition that is evaluated for each element of the specified array. Use the current array element value to reference the element of the array currently being considered.


-------
## IS TRUE FOR ANY:
Whether the specified condition evaluates to true for any value in the specified array.
 - `    ARRAY`:The array whose values will be considered.
 - `    CONDITION`:The condition that is evaluated for each element of the specified array. Use the current array element value to reference the element of the array currently being considered.


-------
## IS USING ABILITY I:
Whether the specified player is using ability i .
 - `    PLAYER`:The player whose ability 1 usage to check.


`IS USING ABILITY 2`:Whether the specified player is using ability 2.
 - `    PLAYER`:The player whose ability 2 usage to check.


-------
## IS USING ULTIMATE:
Whether a player is using an ultimate ability.
 - `    PLAYER`:The player whose ultimate ability usage to check.


-------
## IS WAITING FOR PLAYERS:
Whether the match is waiting for players to join before starting.


-------
## LAST CREATED ENTITY:
A reference to the last effect or icon entity created by the event player (or created at the global level).


-------
## LAST DAMAGE MODIFICATION ID:
An id representing the most recent start damage modification action that was executed by the event player (or executed at the global level).


-------
## LAST DAMAGE OVER TIME ID:
An id representing the most recent damage over time action that was executed by the event player (or executed at the global level).


-------
## LAST HEAL OVER TIME ID:
An id representing the most recent heal over time action that was executed by the event player (or executed at the global level).


-------
## LAST OF:
The value at the end of the specified array. Results in o if the specified array is empty.
 - `    ARRAY`:The array from which the value is acquired.


-------
## LAST TEXT ID:
A reference to the last piece of text created by the event player (or created at the global level) via the create hud text or create in- world text action.


-------
## LEFT:
Shorthand for the directional vector(i, o, 0), which points to the left.


-------
## LOCAL VECTOR OF:
The vector in local coordinates corresponding to the provided vector in world coordinates.
 - `    WORLD VECTOR`:The vector in world coordinates that will be converted to local coordinates.
 - `    RELATIVE PLAYER`:The player to whom the resulting vector will be relative.
 - `    TKANMUKMAI IUN`:Specifies whether the vector should receive a rotation and a translation (usually applied to positions) or only a rotation (usually applied to directions and velocities).


-------
## MATCH ROUND:
The current round of the match, counting up from i


-------
## MATCH TIME:
The amount of time in seconds remaining in the current game mode phase.


-------
## MAX:
The greater of two numbers.
 - `    VALUE`:The left-hand operand. May be any value that results in a number.
 - `    VALUE`:The right-hand operand. May be any value that results in a number.


-------
## MAX HEALTH:
The max health of a player, including armor and shields.
 - `    PLAYER`:The player whose max health to acquire.


-------
## MIN:
The lesser of two numbers.
 - `    VALUE`:The left-hand operand. May be any value that results in a number.
 - `    VALUE`:The right-hand operand. May be any value that results in a number.


-------
## MODULO:
The remainder of the left-hand operand divided by the right-hand operand. Any number modulo zero results in zero.
 - `    VALUE`:The left-hand operand. May be any value that results in a number.
 - `    VALUE`:The right-hand operand. May be any value that results in a number.


-------
## MULTIPLY:
The product of two numbers or vectors. A vector multiplied by a number will yield a scaled vector.
 - `    VALUE`:The left-hand operand. May be any value that results in a number or a vector.
 - `    VALUE`:The right-hand operand. May be any value that results in a number or a vector.


-------
## NEAREST WALKABLE POSITION:
The position closest to the specified position that can be stood on and is accessible from a spawn point.
 - `    POSITION`:The position from which to search for the nearest walkable position.


-------
## NORMALIZE:
The unit-length normalization of a vector.
 - `    VECTOR`:The vector to normalize.


-------
## NOT:
Whether the input is false (or equivalent to false).
 - `    VALUE`:When this input is false (or equivalent to false). Then the not value is true. Otherwise. The not value is false.


-------
## NULL:
The absence of a player. Used when no player is desired for a particular input. Equivalent to the real number o for the purposes of comparison and debugging.


-------
## NUMBER:
A real number constant.
 - `    NUMBER`:


-------
## NUMBER OF DEAD PLAYERS:
The number of dead players on a team or in the match.
 - `    TEAM`:The team or teams on which to count players.


-------
## NUMBER OF DEATHS:
The number of deaths a specific player has earned. This value only accumulates while a game is in progress.
 - `    PLAYER`:The player whose death count to acquire.


-------
## NUMBER OF ELIMINATIONS:
The number of eliminations a specific player has earned. This value only accumulates while a game is in progress.
 - `    PLAYER`:The player whose elimination count to acquire.


-------
## NUMBER OF FINAL BLOWS:
The number of final blows a specific player has earned. This value only accumulates while a game is in progress.
 - `    PLAYER`:The player whose final blow count to acquire.


-------
## NUMBER OF HEROES:
The number of players playing a specific hero on a team or in the match.
 - `    HERO`:The hero to check for play.
 - `    TEAM`:The team or teams on which to check for the hero being played.


-------
## NUMBER OF LIVING PLAYERS:
The number of living players on a team or in the match.
 - `    TEAM`:The team or teams on which to count players.


-------
## NUMBER OF PLAYERS:
The number of players on a team or in the match.
 - `    TEAM`:The team or teams on which to count players.


-------
## NUMBER OF PLAYERS ON OBJECTIVE:
The number of players occupying a payload or control point (either on a team or in the match).
 - `    TEAM`:The team or teams on which to count players.


-------
## OBJECTIVE INDEX:
The control point, payload checkpoint, or payload destination currently active (either o, 1 , or 2). Valid in assault, assault/escort, escort, and control.


-------
## OBJECTIVE POSITION:
The position in the world of the specified objective (either a control point, a payload checkpoint, or a payload destination). Valid in assault, assault/escort, escort, and control.
 - `    NUMBER`:The index of the objective to consider. Starting at o and counting up. Each control point. Payload checkpoint, and payload destination has its own index.


-------
## OPPOSITE TEAM OF:
The team opposite the specified team.
 - `    TEAM`:The team whose opposite to acquire. If all, the result will be all.


-------
## OR:
Whether either of the two inputs are true (or equivalent to true).
 - `    VALUE`:One of the two inputs considered. If either one is true (or equivalent to true), then the or value is true.
 - `    \ TO TRUE), THEN THE OR VALUE IS TR`:One of the two inputs considered. If either one is true (or equivalent to true), then the or value is true.


-------
## PAYLOAD POSITION:
The position in the world of the active payload.


-------
## PAYLOAD PROGRESS PERCENTAGE:
The current progress towards the destination for the active payload (expressed as a percentage).


-------
## PLAYER CARRYING FLAG:
The player carrying a particular team's flag in capture the flag. Results in null if no player is carrying the flag.
 - `    TEAM`:The team whose flag to check.


-------
## PLAYER CLOSEST TO RETICLE:
The player closest to the reticle of the specified player, optionally restricted by team.
 - `    PLAYER`:The player from whose reticle to search for the closest player.
 - `    TEAM`:The team or teams on which to search for "-ie closest player.


-------
## PLAYER VARIABLE:
The current value of a player variable, which is a variable that belongs to a specific player.
 - `    PLAYER`:The player whose variable value to acquire.
 - `    VARIABLE`:The variable whose value to acquire.


-------
## PLAYERS IN SLOT:
The player or array of players who occupy a specific slot in the game.
 - `    5 LOT`:The slot number from which to acquire a player or players. In team games. Each team has slots o through 5. In free-for-au games. Slots are numbered o through 1 1.
 - `    TEAM`:The team or teams from which to acquire a player or players.


-------
## PLAYERS IN VIEW ANGLE:
The players who are within a specific view angle of a specific player's reticle, optionally restricted by team.
 - `    PLAYER`:The player whose view to use for ne check.
 - `    'ILEAM`:The team or teams on which to consider players.
 - `    VIEW ANGLE`:The view angle to compare against in degrees.


-------
## PLAYERS ON HERO:
The array of players playing a specific hero on a team or in the match.
 - `    HERO`:The hero to check for play.
 - `    TEAM`:The team or teams on which to check for the hero being played.


-------
## PLAYERS WITHIN RADIUS:
An array containing all players within a certain distance of a position, optionally restricted by team and line of sight.
 - `    CENTER`:The center position from which to measure distance.
 - `    RADIUS`:The radius in meters inside which players must be in order to be included in the resulting array.
 - `    TEAM`:The team or teams to which a player must belong to be included in the resulting array.
 - `    LOS CHECK`:Specifies whether and how a player must pass a line-of-sight check to be included in the resulting array.


-------
## POINT CAPTURE PERCENTAGE:
The current progress towards capture for the active control point (expressed as a percentage).


-------
## POSITION OF:
The current position of a player as a vector.
 - `    PLAYER`:The player whose position to acquire.


-------
## RAISE TO POWER:
The left-hand operand raised to the power of the right-hand operand. If the left-hand operand is negative, the result is always zero.
 - `    VALUE`:The left-hand operand. May be any value that results in a number.
 - `    VALUE`:The right-hand operand. May be any value that results in a number.


-------
## RANDOM INTEGER:
A random integer between the specified min and max, inclusive.
 - `    MIN`:The smallest integer allowed. If a real number is provided to this input. It is rounded to the nearest integer.


-------
## RANDOM REAL:
A random real number between the specified min and max.
 - `    MIN`:The smallest real number allowed.


-------
## RANDOM VALUE IN ARRAY:
A random value from the specified array.
 - `    ARRAY`:The array from which to randomly take a value. If a non-array value is provided. The result is simply the provided value.


-------
## RANDOMIZED ARRAY:
A copy of the specified array with the values in a random order.
 - `    ARRAY`:The array whose copy will be randomized.


-------
## RAY CAST HIT NORMAL:
The surface normal at the ray cast hit position (or from end pos to start pos if no hit occurs).
 - `    START POS`:The start position for the ray cast. If a player is provided, a position 2 meters above the player's feet is used.
 - `    END P05`:The end position for the ray cast. If a player is provided. A position 2 meters above the player's feet is used.


-------
## RAY CAST HIT PLAYER:
The player hit by the ray cast (or null if no player is hit).
 - `    START POS`:The start position for the ray cast. If a player is provided, a position 2 meters above the player's feet is used.
 - `    END P05`:The end position for the ray cast. If a player is provided. A position 2 meters above the player's feet is used.


-------
## RAY CAST HIT POSITION:
The position where the ray cast hits a surface, object, or player (or the end pos if no hit occurs).
 - `    START POS`:The start position for the ray cast. If a player is provided, a position 2 meters above the player's feet is used.
 - `    END P05`:The end position for the ray cast. If a player is provided. A position 2 meters above the player's feet is used.


-------
## REMOVE FROM ARRAY:
A copy of an array with one or more values removed (if found).
 - `    ARRAY`:The array from which to remove values.
 - `    VALUE`:The value to remove from the array (if found). If this value is itself an array. Each matching element is removed.


-------
## RIGHT:
Shorthand for the directional vector(-i , o, 0), which points to the right.


-------
## ROUND TO INTEGER:
The integer to which the specified value rounds.
 - `    VALUE`:The real number to round.
 - `    ROUNDING TYPE`:Determines the direction in which the value will be rounded.


-------
## SCORE OF:
The current score of a player. Results in o if the game mode is not free-for-all.
 - `    PLAYER`:The player whose score to acquire.


-------
## SINE FROM DEGREES:
Sine of the specified angle in degrees.
 - `    ANGLE`:Angle in degrees.


-------
## SINE FROM RADIANS:
Sine of the specified angle in radians.
 - `    ANGLE`:Angle in radians.


-------
## SLOT OF:
The slot number of the specified player. In team games, each team has slots o through 5. In free-for-all games, slots are numbered o through i i
 - `    PLAYER`:The player whose slot number to acquire.


-------
## SORTED ARRAY:
A copy of the specified array with the values sorted according to the value rank that is evaluated for each element.
 - `    ARRAY`:The array whose copy will be sorted.
 - `    VALUE RANK`:The value that is evaluated for each element of the copied array. "-ie array is sorted by this rank in ascending order. Use the current array element value to reference the element of the array currently being considered.


-------
## SPEED OF:
The current speed of a player in meters per second.
 - `    PLAYER`:The player whose speed to acquire.


-------
## SPEED OF IN DIRECTION:
The current speed of a player in a specific direction in meters per second.
 - `    PLAYER`:The player whose speed to acquire.
 - `    DIRECTION`:The direction of travel in which to measure the player's speed.


-------
## SQUARE ROOT:
The square root of the specified value.
 - `    VALUE`:The real number value whose square root will be computed. Negative values result in zero.


-------
## STRING:
Text formed from a selection of strings and specified values.
 - `    STRING`:
 - `    {0}`:The value that will be converted to text and used to replace
 - `    {l}`:The value that will be converted to text and used to replace
 - `    {2}`:The value that will be converted to text and used to replace


-------
## SUBTRACT:
The difference between two numbers or vectors.
 - `    VALUE`:The left-hand operand. May be any value that results in a number or a vector.
 - `    VALUE`:The right-hand operand. May be any value that results in a number or a vector.


-------
## TEAM:
A team constant. The all option represents both teams in a team game or all players in a free-for-all game.
 - `    TEAM`:A team constant. The all option represents both teams in a team game or all players in a free-for-all game.


-------
## TEAM OF:
The team of a player. If the game mode is free-for-all, the team is considered to be all.
 - `    PLAYER`:The player whose team to acquire.


-------
## TEAM SCORE:
The current score for the specified team. Results in o in free-for-all game modes.
 - `    TEAM`:The team whose score to acquire.


-------
## THROTTLE OF:
The directional input of a player, represented by a vector with horizontal input on the x component (positive to the left) and vertical input on the z component (positive upward).
 - `    PLAYER`:The player whose directional input to acquire.


-------
## TOTAL TIME ELAPSED:
The total time in seconds that have elapsed since the game instance was created (including setup time and transitions).


-------
## TRUE:
The boolean value of true.


-------
## ULTIMATE CHARGE PERCENT:
The current ultimate ability charge percentage of a player.
 - `    PLAYER`:The player whose ultimate charge percentage to acquire.


-------
## UP:
Shorthand for the directional vector(o, l, 0), which points upward.


-------
## VALUE IN ARRAY:
The value found at a specific element of an array. Results in o if the element does not exist.
 - `    ARRAY`:The array whose element to acquire.
 - `    INDEX`:The index of the element to acquire.


``:A vector composed of three real numbers (x, y, z) where x is left, y is up, and z is forward. Vectors are used for position, direction, and velocity.


-------
## VECTOR TOWARDS:
The displacement vector from one position to another.
 - `    START POS`:The position from which the resulting displacement vector begins.
 - `    END P05`:The position at which the resulting displacement vector ends.


-------
## VELOCITY OF:
The current velocity of a player as a vector. If the player is on a surface, the y component of this velocity will be o, even when traveling up or down a slope.
 - `    PLAYER`:The player whose velocity to acquire.


-------
## VERTICAL ANGLE FROM DIRECTION:
The vertical angle in degrees corresponding to the specified direction vector.
 - `    DIRECTION`:The direction vector from which to acquire a vertical angle in degrees. The vector is unitized before calculation begins.


-------
## VERTICAL ANGLE TOWARDS:
The vertical angle in degrees from a player's current forward direction to the specified position. The result is positive if the position is below the player. Otherwise, the result is zero or negative.
 - `    PLAYER`:The player from whose current facing the angle begins.
 - `    POSITION`:The position in the world where the angle ends.


-------
## VERTICAL FACING ANGLE OF:
The vertical angle in degrees of a player's current facing relative to the world. This value increases as the player looks down.
 - `    PLAYER`:The player whose vertical facing angle to acquire.


-------
## VERTICAL SPEED OF:
The current vertical speed of a player in meters per second. This measurement excludes all horizontal motion, including motion while traveling up and down slopes.
 - `    PLAYER`:The player whose vertical speed to acquire.


-------
## VICTIM:
The player that received the damage for the event currently being processed by this rule. May be the same as the attacker or the event player.


-------
## WORLD VECTOR OF:
The vector in world coordinates corresponding to the provided vector in local coordinates.
 - `    LOCAL VECTOR`:The vector in local coordinates that will be converted to world coordinates.
 - `    RELATIVE PLAYER`:The player to whom the local vector is relative.
 - `    TKANMUKMAI IUN`:Specifies whether the vector should receive a rotation and a translation (usually applied to positions) or only a rotation (usually applied to directions and velocities).


-------
## X COMPONENT OF:
The x component of the specified vector, usually representing a leftward amount.
 - `    VALUE`:The vector from which to acquire the x component.


-------
## Y COMPONENT OF:
The y component of the specified vector, usually representing an upward amount.
 - `    VALUE`:The vector from which to acquire the y component.


-------
## Z COMPONENT OF:
The z component of the specified vector, usually representing a forward amount.
 - `    VALUE`:The vector from which to acquire the z component.
