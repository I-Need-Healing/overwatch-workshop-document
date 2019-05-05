

-------
## ABORT:
Stops execution of the action list.


-------
## ABORT IF:
Stops execution of the action list if this action's condition evaluates to true. If it does not, execution continues with the next action.
 - `    CONDITION`:Specifies whether the execution is stopped.


-------
## ABORT IF CONDITION IS FALSE:
Stops execution of the action list if at least one condition in the condition list is false. If all conditions are true, execution continues with the next action.


-------
## ABORT IF CONDITION IS TRUE:
Stops execution of the action list if all conditions in the condition list are true. If any are false, execution continues with the next action.


-------
## ALLOW BUTTON:
Undoes the effect of the disallow button action for one or more players.
 - `    PLAYER`:The player or players whose button is being reenabled.
 - `    BUTTON`:The logical button that is being reenabled.


-------
## APPLY IMPULSE:
Applies an instantaneous change in velocity to the movement of one or more players.
 - `    PLAYER`:The player or players whose velocity will be changed.
 - `    DIRECTION`:The unit direction in which the impulse will be applied. This value is normalized internally.
 - `    SPEED`:The magnitude of the change to the velocities of the player or players.
 - `    RELATIVE`:Specifies whether direction is relative to world coordinates or the local coordinates of the player or players.


-------
## BIG MESSAGE:
Displays a large message above the reticle that is visible to specific players.
 - `    VISIBLE TO`:One or more players who will see the message.
 - `    HEADER`:The message to be displayed.


-------
## CHASE GLOBAL VARIABLE AT RATE:
3radually modifies the value of a global variable at a specific rate. Global variable is a variable that belongs to the game itself.)
 - `    VARIABLE`:Specifies which global variable to modify gradually.
 - `    DESTINATION`:The value that the global variable will eventually reach. "-ie type of this value may be either a number or a vector. Though the variable's existing value must be of the same type before the chase begins.
 - `    RATE`:The amount of change that will happen to the variable's value each second.
 - `    REEVALUATION`:Specifies which of this action's inputs will be continuously reevaluated. This action will keep asking for and using new values from reevaluated inputs.


-------
## CHASE GLOBAL VARIABLE OVER TIME:
Gradually modifies the value of a global variable over time. (a global variable is a variable that belongs to the game itself.)
 - `    VARIABLE`:Specifies which global variable to modify gradually.
 - `    DESTINATION`:The value that the global variable will eventually reach. "-ie type of this value may be either a number or a vector. Though the variable's existing value must be of the same type before the chase begins.
 - `    DURATION`:The amount of time, in seconds, over which the variable's value will approach the destination.
 - `    REEVALUATION`:Specifies which of this action's inputs will be continuously reevaluated. This action will keep asking for and using new values from reevaluated inputs.


-------
## CHASE PLAYER VARIABLE AT RATE:
Gradually modifies the value of a player variable at a specific rate. (a player variable is a variable that belongs to a specific player.)
 - `    PLAYER`:The player whose variable will gradually change. If multiple players are provided, each of their variables will change independently.
 - `    VARIABLE`:Specifies which of "-ie player's variables to modify gradually.
 - `    DESTINATION`:The value that the player variable will eventually reach. The type of this value may be either a number or a vector. Though the variable's existing value must be of the same type before the chase begins.
 - `    RATE`:The amount of change that will happen to the variable's value each second.


-------
## CHASE PLAYER VARIABLE OVER TIME:
Gradually modifies the value of a player variable over time. (a player variable is a variable that belongs to a specific player.)
 - `    PLAYER`:The player whose variable will gradually change. If multiple players are provided, each of their variables will change independently.
 - `    VARIABLE`:Specifies which of "-ie player's variables to modify gradually.
 - `    DESTINATION`:The value that the player variable will eventually reach. The type of this value may be either a number or a vector. Though the variable's existing value must be of the same type before the chase begins.
 - `    DURATION`:The amount of time, in seconds, over which the variable's value will approach the destination.


-------
## CLEAR STATUS:
Clears a status that was applied from a set status action from one or more players.
 - `    PLAYER`:The player or players from whom the status will be removed.
 - `    STATUS`:The status to be removed from the player or players.


-------
## COMMUNICATE:
Causes one or more players to use an emote, voice line, or other equipped communication.
 - `    PLAYER`:The player or players to perform the communication.
 - `    TYPE`:The type of communication.


-------
## CREATE EFFECT:
Creates an in-world effect entity. This effect entity will persist until destroyed. To obtain a reference to this entity, use the last created entity value. This action will fail if too many entities have been created.
 - `    VISIBLE TO`:One or more players who will be able to see the effect.
 - `    TYPE`:The type of effect to be created.
 - `    COLOR`:The color of the effect to be created. If a particular team is chosen, the effect will either be red or blue. Depending on whether the team is hostile to the viewer. Does not apply to sound effects.
 - `    POSITION`:The effect's position. If this value is a player, then the effect will move along with the player. Otherwise, the value is interpreted as a position in the world.


-------
## CREATE HUD TEXT:
Reates hud text visible to specific players at a specific location on screen. This text will persist until destroyed. To obtain a eference to this text, use the last text id value. This action will fail if do many text elements have been created.
 - `    VISIBLE TO`:One or more players who will see the hud text.
 - `    HEADER`:The text to be displayed (can be blank)
 - `    SUBHEADER`:The subheader text to be displayed (can be blank)
 - `    TEXT`:The body text to be displayed (can be blank)


-------
## CREATE ICON:
Creates an in-world icon entity. This icon entity will persist until destroyed. To obtain a reference to this entity, use the last created entity value. This action will fail if too many entities have been created.
 - `    VISIBLE TO`:One or more players who will be able to see the icon.
 - `    POSITION`:The icon's position. If this value is a player, then the icon will appear above the player's head. Otherwise, the value is interpreted as a position in the world.
 - `    ICON`:The icon to be created.
 - `    REEVALUATION`:Specifies which of this action's inputs will be continuously reevaluated. The icon will keep asking for and using new values from reevaluated inputs.


-------
## CREATE lN-WORLD TEXT:
Reates in-world text visible to specific players at a specific position the world. This text will persist until destroyed. To obtain a eference to this text, use the last text id value. This action will fail if do many text elements have been created.
 - `    VISIBLE TO`:One or more players who will see the in-world text.
 - `    HEADER`:The text to be displayed.
 - `    POSITION`:The texts position. If this value is a player, then the text will appear above the player's head. Otherwise, the value is interpreted as a position in the world.
 - `    SCALE`:The texts scale.


-------
## DAMAGE:
Applies instantaneous damage to one or more players, possibly killing the players.
 - `    PLAYER`:The player or players who will receive damage.
 - `    DAMAGE R`:The player who will receive credit for the damage. A damager of null indicates no player will receive credit.
 - `    AMO U NT`:The amount of damage to apply. This amount may be modified by buffs, debuffs. Or armor.


-------
## DECLARE MATCH DRAW:
Qstantly ends the match in a draw. This action has no effect in free- or-all modes.


-------
## DECLARE PLAYER VICTORY:
Instantly ends the match with the specific player as the winner. This action only has an effect in free-for-all modes.
 - `    PLAYER`:The winning player.


-------
## DECLARE ROUND VICTORY:
•eclare a team as the current round winner. This only works in the ontrol and elimination game modes
 - `    ROUND WINNING TEA`:Round winning team


-------
## DECLARE TEAM VICTORY:
Instantly ends the match with the specified team as the winner. This action has no effect in free-for-all modes.
 - `    TEAM`:The winning team.


-------
## DESTROY ALL EFFECTS:
Destroys all effect entities created by create effect.


-------
## DESTROY ALL HUD TEXT:
•estroys all hud text that was created by the create hud text action.


-------
## DESTROY ALL ICONS:
Destroys all icon entities created by create icon.


-------
## DESTROY ALL IN-WORLD TEXT:
Destroys all in-world text created by create in-world text.


-------
## DESTROY EFFECT:
Destroys an effect entity that was created by create effect.
 - `    ENTITY`:Specifies which effect entity to destroy. This entity may be last created entity or a variable into which last created entity was earlier stored.


-------
## DESTROY HUD TEXT:
Destroys hud text that was created by create hud text.
 - `    TEXT ID`:Specifies which hud text to destroy. This id may be last text id or a variable into which last text id was earlier stored.


-------
## DESTROY ICON:
Destroys an icon entity that was created by create icon.
 - `    ENTITY`:None


-------
## DESTROY ICON:
Destroys an icon entity that was created by create icon.
 - `    ENTITY`:Specifies which icon entity to destroy. This entity may be last created entity or a variable into which last created entity was earlier stored.


-------
## DESTROY lN-WORLD TEXT:
Destroys in-world text that was created by create in-world text.
 - `    TEXT ID`:Specifies which in-world text to destroy. This id may be last text id or a variable into which last text id was earlier stored.


-------
## DISABLE BUILT-IN GAME MODE ANNOUNCER:
Disables game mode announcements from the announcer until reenabled or the match ends.


-------
## DISABLE BUILT-IN GAME MODE COMPLETION:
Disables completion of the match from the game mode itself, only allowing the match to be completed by scripting commands.


-------
## DISABLE BUILT-IN GAME MODE MUSIC:
Disables all game mode music until reenabled or the match ends.


-------
## DISABLE BUILT-IN GAME MODE RESPAWNING:
Disables automatic respawning for one or more players, only allowing respawning by scripting commands.
 - `    PLAYERS`:The player or players whose respawning is affected.


-------
## DISABLE BUILT-IN GAME MODE SCORING:
)isables changes to player and team scores from the game mode tself, only allowing scores to be changed by scripting commands.


-------
## DISABLE DEATH SPECTATE ALL PLAYERS:
Indoes the effect of the enable death spectate all players action for or more players.
 - `    PLAYER`:The player or players whose default death spectate behavior is restored.


-------
## DISABLE DEATH SPECTATE TARGET HUD:
Ndoes the effect of the enable death spectate target hud action for or more players.
 - `    PLAYER`:The player or players who will revert to seeing their own hud while death spectating.


-------
## DISALLOW BUTTON:
Disables a logical button for one or more players such that pressing it has no effect.
 - `    PLAYER`:The player or players whose button is being disabled.
 - `    BUTTON`:The logical button that is being disabled.


-------
## ENABLE BUILT-IN GAME MODE ANNOUNCER:
Undoes the effect of the disable built-in game mode announcer action.


-------
## ENABLE BUILT-IN GAME MODE COMPLETION:
Undoes the effect of the disable built-in game mode completion action.


-------
## ENABLE BUILT-IN GAME MODE MUSIC:
Undoes the effect of the disable built-in game mode music action.


-------
## ENABLE BUILT-IN GAME MODE RESPAWNING:
Undoes the effect of the disable built-in game mode respawning action for one or more players.
 - `    PLAYERS`:The player or players whose respawning is affected.


-------
## ENABLE BUILT-IN GAME MODE SCORING:
Undoes the effect of the disable built-in game mode scoring action.


-------
## ENABLE DEATH SPECTATE ALL PLAYERS:
Allows one or more players to spectate all players when dead, as opposed to only allies.
 - `    PLAYER`:The player or players who will be allowed to spectate all players.


-------
## ENABLE DEATH SPECTATE TARGET HUD:
'auses one or more players to see their spectate target's hud instead their own while death spectating.
 - `    PLAYER`:The player or players who will begin seeing their spectate targets hud while death spectating.


-------
## GO TO ASSEMBLE HEROES:
Returns the match to the assemble heroes phase of the game mode. Only works if the game is in progress.


-------
## HEAL:
Provides an instantaneous heal to one or more players. This heal will not resurrect dead players.
 - `    PLAYER`:The player or players whose health will be restored.
 - `    HEALER`:The player who will receive credit for the healing. A healer of null indicates no player will receive credit.
 - `    AMO U NT`:The amount of healing to apply. This amount may be modified by bufi or debuffs. Healing is capped by each player's max health.


-------
## KILL:
Instantly kills one or more players.
 - `    PLAYER`:The player or players who will be killed.
 - `    KILLER`:The player who will receive credit for the kill. A killer of null indicates no player will receive credit.


-------
## LOOP:
2estarts the action list from the beginning. To prevent an infinite .oop, a wait action must execute between the start of the action list this action.


-------
## LOOP IF:
Estarts the action list from the beginning if this action's condition valuates to true. If it does not, execution continues with the next ction. To prevent an infinite loop, a wait action must execute etween the start of the action list and this action.
 - `    CONDITION`:Specifies whether the loop will occur.


-------
## LOOP IF CONDITION IS FALSE:
!estarts the action list from the beginning if at least one condition the condition list is false. If all conditions are true, execution


-------
## LOOP IF CONDITION IS TRUE:
Restarts the action list from the beginning if every condition in the condition list is true. If any are false, execution continues with the next action. To prevent an infinite loop, a wait action must execute between the start of the action list and this action.


-------
## MODIFY GLOBAL VARIABLE:
Modifies the value of a global variable, which is a variable that belongs to the game itself.
 - `    VARIABLE`:The global variable to modify.
 - `    OPERATION`:The way in which the variable's value will be changed. Options include standard arithmetic operations as well as array operations for appending and removing values.
 - `    VALUE`:The value used for the modification. For arithmetic operations, this is the second of the two operands. With the other being the variable's existing value. For array operations, this is the value to


-------
## MODIFY PLAYER SCORE:
Modifies the score (kill count) of one or more players. This action only has an effect in free-for-all modes.
 - `    PLAYER`:The player or players whose score will change.
 - `    SCORE`:The amount "-ie score will increase or decrease. If positive, the score wu increase. If negative. The score will decrease.


-------
## MODIFY PLAYER VARIABLE:
Modifies the value of a player variable, which is a variable that belongs to a specific player.
 - `    PLAYER`:The player whose variable will be modified. If multiple players are provided, each of their variables will be set.
 - `    VARIABLE`:Specifies which of "-ie player's variables to modify.
 - `    OPERATION`:The way in which the variable's value will be changed. Options include standard arithmetic operations as well as array operations for appending and removing values.
 - `    VALU E`:The value used for the modification. For arithmetic operations, this is the second of the two operands. With the other being the variable's existing value. For array operations, this is the value to


-------
## MODIFY TEAM SCORE:
\odifies the score of one or both teams. This action has no effect in ree-for-all modes or modes without a team score.
 - `    TEAM`:The team or teams whose score will be changed.
 - `    SCORE`:The amount "-ie score will increase or decrease. If positive, the score wu increase. If negative. The score will decrease.


-------
## PAUSE MATCH TIME:
Pauses the match time. Players, objective logic, and game mode advancement criteria are unaffected by the pause.


-------
## PLAY EFFECT:
Lays an effect at a position in the world. The lifetime of this effect is hort, so it does not need to be updated or destroyed.
 - `    VISIBLE TO`:One or more players who will be able to see the effect.
 - `    TYPE`:The type of effect to be created.
 - `    COLOR`:The color of the effect to be created. If a particular team is chosen, the effect will either be red or blue. Depending on whether the team is hostile to the viewer.
 - `    POSITION`:The effect's position. If this value is a player, then the effect will play at the player's position. Otherwise, the value is interpreted as a position in the world.


-------
## PRELOAD HERO:
Reemptively loads the specified hero or heroes into memory using he skins of the specified player or players, available memory ermitting. Useful whenever rapid hero changing is possible and the 'ext hero is known.
 - `    PLAYER`:The player or players who will begin preloading a hero or heroes. Only one preload hero action will be active at a time for a given player.
 - `    HERO`:The hero or heroes to begin preloading for the specified player or players. When multiple heroes are specified in an array. The heroes towards the beginning of the array are prioritized.


-------
## PRESS BUTTON:

 - `    PLAYER`:The player or players for whom virtual button input will be forced.
 - `    BUTTON`:The button to be pressed.


-------
## RESET PLAYER HERO AVAILABILITY:
U-stores the list of heroes available to one or more players to the -1st specified by the game settings. If a player's current hero becomes jnavailable, the player is forced to choose a different hero and u-spawn at an appropriate spawn location.
 - `    PLAYER`:The player or players whose hero list is being reset.


-------
## RESPAWN:
Respawns one or more players at an appropriate spawn location with full health, even if they were already alive.
 - `    PLAYER`:The player or players to respawn.


-------
## RESURRECT:
Instantly resurrects one or more players at the location they died with no transition.
 - `    PLAYER`:The player or players who will be resurrected.


-------
## SET ABILITY I ENABLED:
Enables or disables ability i for one or more players.
 - `    PLAYER`:The player or players whose access to ability 1 is affected.
 - `    ENABLED`:Specifies whether the player or players are able to use ability 1 . Expects a boolean value such as true. False. Or compare.


`SET ABILITY 2 ENABLED`:Enables or disables ability 2 for one or more players.
 - `    PLAYER`:The player or players whose access to ability 2 is affected.
 - `    ENABLED`:Specifies whether the player or players are able to use ability 2. Expects a boolean value such as true. False. Or compare.


-------
## SET AIM SPEED:
Sets the aim speed of one or more players to a percentage of their normal aim speed.
 - `    PLAYER`:The player or players whose aim speed will be set.
 - `    TURN SPEED PERCENT`:The percentage of normal aim speed to which the player or players wu set their aim speed.


-------
## SET DAMAGE DEALT:
Sets the damage dealt of one or more players to a percentage of their raw damage dealt.
 - `    PLAYER`:The player or players whose damage dealt will be set.
 - `    DAMAGE DEALT PERCI`:The percentage of raw damage dealt to which the player or players wu set their damage dealt.


-------
## SET DAMAGE RECEIVED:
E-ts the damage received of one or more players to a percentage of heir raw damage received.
 - `    PLAYER`:The player or players whose damage received will be set.
 - `    DAMAGE RECEIVED PE`:The percentage of raw damage received to which the player or players will set their damage received.


-------
## SET FACING:
Sets the facing of one or more players to the specified direction.
 - `    PLAYER`:The player or players whose facing will be set.
 - `    DIRECTION`:The unit direction in which the player or players will face. This value is normalized internally.
 - `    RELATIVE`:Specifies whether direction is relative to world coordinates or the local coordinates of the player or players.


-------
## SET GLOBAL VARIABLE:
Stores a value into a global variable, which is a variable that belongs to the game itself.
 - `    VARIABLE`:Specifies which global variable to store "-ie value into.
 - `    VALUE`:The value that will be stored.


-------
## SET GLOBAL VARIABLE AT INDEX:
Finds or creates an array on a global variable, which is a variable rhat belongs to the game itself, then stores a value in the array at [he specified index.
 - `    VARIABLE`:Specifies which global variable's value is the array to modify. If the variable's value is not an array. Then its value becomes an empty array.
 - `    INDEX`:The index of the array to modify. If the index is beyond the end of the array. The array is extended with new elements given a value of zero.
 - `    VALU E`:The value that will be stored into the array.


-------
## SET GRAVITY:
E-ts the movement gravity for one or more players to a percentage regular movement gravity.
 - `    PLAYER`:The player or players whose movement gravity will be set.
 - `    GRAVITY PERCENT`:The percentage of regular movement gravity to which the player 0' players will set their personal movement gravity.


-------
## SET HEALING DEALT:
Sets the healing dealt of one or more players to a percentage of their raw healing dealt.
 - `    PLAYER`:The player or players whose healing dealt will be set.
 - `    HEALING DEALT PE RCE`:


-------
## SET HEALING RECEIVED:
;ets the healing received of one or more players to a percentage of •heir raw healing received.
 - `    PLAYER`:The player or players whose healing received will be set.
 - `    HEALING RECEIVED PE`:The percentage of raw healing received to which the player or players will set their healing received.


-------
## SET INVISIBLE:
Causes one or more players to become invisible to either all other players or just enemies.
 - `    PLAYER`:The player or players who will become invisible.
 - `    INVISIBLE TO`:Specifies for whom the player or players will be invisible.


-------
## SET MATCH TIME:
;ets the current match time (which is visible at the top of the screen). •his can be used to shorten or extend the duration of a match or •o change the duration of assemble heroes or setup.
 - `    TIME`:The match time in seconds.


-------
## SET MAX HEALTH:
E-ts the max health of one or more players as a percentage of their max health. This action will ensure that a player's current *ealth will not exceed the new max health.
 - `    PLAYER`:The player or players whose max health will be set.
 - `    HEALTH PERCENT`:The percentage of raw max health to which the player or players wu set their max health.


-------
## SET MOVE SPEED:
Sets the move speed of one or more players to a percentage of their raw move speed.
 - `    PLAYER`:The player or players whose move speed will be set.
 - `    MOVE SPEED PERCENT`:The percentage of raw move speed to which the player or players wu set their move speed.


-------
## SET OBJECTIVE DESCRIPTION:
Sets the text at the top center of the screen that normally describes the objective to a message visible to specific players.
 - `    VISIBLE TO`:One or more players who will see the message.
 - `    HEADER`:The message to be displayed.
 - `    REEVALUATION`:Specifies which of this action's inputs will be continuously reevaluated. The message will keep asking for and using new values from reevaluated inputs.


-------
## SET PLAYER ALLOWED HEROES:
Iets the list of heroes available to one or more players. If a player's iirrent hero becomes unavailable, the player is forced to choose a )ifferent hero and respawn at an appropriate spawn location.
 - `    PLAYER`:The player or players whose hero list is being set.
 - `    HERO`:The hero or heroes that will be available. If no heroes are provided. The action has no effect.


-------
## SET PLAYER SCORE:
Sets the score (kill count) of one or more players. This action only has an effect in free-for-all modes.
 - `    PLAYER`:The player or players whose score will be set.
 - `    SCORE`:The score that will be set.


-------
## SET PLAYER VARIABLE:
Stores a value into a player variable, which is a variable that belongs to a specific player.
 - `    PLAYER`:The player whose variable will be set. If multiple players are provided, each of their variables will be set.
 - `    VARIABLE`:Specifies which of "-ie player's variables to store the value into.
 - `    VALUE`:The value that will be stored.


-------
## SET PLAYER VARIABLE AT INDEX:

 - `    PLAYER`:The player whose variable will be modified. If multiple players are provided, each of their variables will be modified.
 - `    VARIABLE`:Specifies which player variable's value is the array to modify. If the variable's value is not an array. Then its value becomes an empty array.
 - `    INDEX`:The index of the array to modify. If the index is beyond the end of the array. The array is extended with new elements given a value of zero.
 - `    VALU E`:The value that will be stored into the array.


-------
## SET PRIMARY FIRE ENABLED:
Enables or disables primary fire for one or more players.
 - `    PLAYER`:The player or players whose access to primary fire is affected.
 - `    ENABLED`:Specifies whether the player or players are able to use primary fire. Expects a boolean value such as true. False. Or compare.


-------
## SET PROJECTILE GRAVITY:
Sets the projectile gravity for one or more players to a percentage of regular projectile gravity.
 - `    PLAYER`:The player or players whose projectile gravity will be set.
 - `    PROJECTILE GRAVITY F`:The percentage of regular projectile gravity to which the player or players will set their personal projectile gravity.


-------
## SET PROJECTILE SPEED:
Iets the projectile speed for one or more players to a percentage of projectile speed.
 - `    PLAYER`:The player or players whose projectile speed will be set.
 - `    PROJECTILE SPEED PER`:The percentage of regular projectile speed to which the player or players will set their personal projectile speed.


-------
## SET RESPAWN MAX TIME:
Sets the duration between death and respawn for one or more players. For players that are already dead when this action is executed, the change takes effect on their next death.
 - `    PLAYER`:The player or players whose respawn max time is being defined.
 - `    TIME`:The duration between death and respawn in seconds.


-------
## SET SECONDARY FIRE ENABLED:
Enables or disables secondary fire for one or more players.
 - `    PLAYER`:The player or players whose access to secondary fire is affected.
 - `    ENABLED`:Specifies whether the player or players are able to use secondary fire. Expects a boolean value such as true, false. Or compare.


-------
## SET SECONDARY FIRE ENABLED:
Enables or disables secondary fire for one or more players.
 - `    PLAYER`:The player or players whose access to secondary fire is affected.
 - `    ENABLED`:Specifies whether the player or players are able to use secondary fire. Expects a boolean value such as true, false. Or compare.


-------
## SET SLOW MOTION:
Sets the simulation rate for the entire game, including all players, projectiles, effects, and game mode logic.
 - `    SPEED PERCENT`:The simulation rate as a percentage of normal speed. Only rates up to 100% are allowed.


-------
## SET STATUS:
Applies a status to one or more players. This status will remain in effect for the specified duration or until it is cleared by the clear status action.
 - `    PLAYER`:The player or players to whom the status will be applied.
 - `    ASSISTER`:Specifies a player to be awarded assist credit should the affected player or players be killed while the status is in effect. An assister of null indicates no player will receive credit.
 - `    STATUS`:The status to be applied to the player or players. These behave similarly to statuses applied from hero abilities.
 - `    DURATION`:The duration of the status in seconds. To have a status that lasts until a clear status action is executed. Provide an arbitrarily long duration such as 9999.


-------
## SET TEAM SCORE:
Sets the score for one or both teams. This action has no effect in free-for-all modes or modes without a team score.
 - `    TEAM`:The team or teams whose score will be set.
 - `    SCORE`:The score that will be set.


-------
## SET ULTIMATE ABILITY ENABLED:
Enables or disables the ultimate ability of one or more players.
 - `    PLAYER`:The player or players whose access to their ultimate ability is affected.
 - `    ENABLED`:Specifies whether the player or players are able to use their ultimate ability. Expects a boolean value such as true. False, or compare.


-------
## SET ULTIMATE CHARGE:
Ets the ultimate charge for one or more players as a percentage of iaximum charge.
 - `    PLAYER`:The player or players whose ultimate charge will be set.
 - `    CHARGE PERCENT`:The percentage of maximum charge.


-------
## SKIP:
Skips execution of a certain number of actions in the action list.
 - `    NUMBER OF ACTIONS`:The number of actions to skip, not including this action.


-------
## SKIP IF:
Skips execution of a certain number of actions in the action list if this action's condition evaluates to true. If it does not, execution continues with the next action.
 - `    CONDITION`:Specifies whether the skip occurs.
 - `    NUMBER OF ACTIONS`:The number of actions to skip, not including this action.


-------
## SMALL MESSAGE:
Displays a small message beneath the reticle that is visible to specific players.
 - `    VISIBLE TO`:One or more players who will see the message.
 - `    HEADER`:The message to be displayed.


-------
## START ACCELERATING:
Starts accelerating one or more players in a specified direction.
 - `    PLAYER`:The player or players that will begin accelerating.
 - `    DIRECTION`:The unit direction in which the acceleration will be applied. This value is normalized internally.
 - `    RATE`:The rate of acceleration in meters per second squared. This value may need to be quite high in order to overcome gravity and/or surface friction.
 - `    MAX SPEED`:The speed at which acceleration will stop for the player or players. It may not be possible to reach this speed due to gravity and/or surface friction.


-------
## START CAMERA:
Places your camera at a location, facing a direction.
 - `    PLAYER`:The player or players whose cameras will be placed at the location.
 - `    EYE POSITION`:The position of the camera. Reevaluates continuously.
 - `    LOOK AT POSITION`:Where the camera looks at. Reevaluates continuously.


-------
## START DAMAGE MODIFICATION:
,tarts modifying how much damage one or more receivers will !eceive from one or more damagers. A reference to this damage aodification can be obtained from the last damage modification id /alue. This action will fail if too many damage modifications have
 - `    RECEIVERS`:The player or players whose incoming damage will be modified (when attacked by the damagers).
 - `    DAMAGERS`:The player or players whose outgoing damage will be modified (when attacking the receivers).
 - `    DAMAGE PERCENT`:The percentage of damage that will apply to receivers when attacked by damagers.
 - `    REEVALUATION`:Specifies which of this action's inputs will be continuously reevaluated. This action will keep asking for and using new values from reevaluated inputs.


-------
## START DAMAGE OVER TIME:
Starts an instance of damage over time. This dot will persist for the specified duration or until stopped by script. To obtain a reference ro this dot, use the last damage over time id value.
 - `    PLAYER`:One or more players who will receive the damage over time.
 - `    DAMAGE R`:The player who will receive credit for the damage. A damager of null indicates no player will receive credit.
 - `    DURATION`:The duration of the damage over time in seconds. To have a dot thai lasts until stopped by script, provide an arbitrarily long duration such as 9999.
 - `    DAMAGE PER SECONE`:The damage per second for the damage over time.


-------
## START FACING:
Starts turning one or more players to face the specified direction.
 - `    PLAYER`:The player or players who will start iurning.
 - `    DIRECTION`:The unit direction in which the player or players will eventuauy face. This value is normalized internally.
 - `    TURN RATE`:The turn rate in degrees per second.
 - `    RELATIVE`:Specifies whether direction is relative to world coordinates or the local coordinates of the player or players.


-------
## START FORCING PLAYER TO BE HERO:
Tarts forcing one or more players to be a specific hero and, if 'ecessary, respawns them immediately in their current location. This "ill be the only hero available to the player or players until the top forcing player to be hero action is executed.
 - `    PLAYER`:The player or players who will be forced to be a specific hero.
 - `    HERO`:The hero that the player or players will be forced to be.


-------
## START FORCING SPAWN ROOM:
Forces a team to spawn in a particular spawn room, regardless of the spawn room normally used by the game mode. This action only has an effect in assault, hybrid, and payload maps.
 - `    TEAM`:The team whose spawn room will be forced.
 - `    ROOM`:The number of the spawn room to be forced. O is the first spawn room, 1 the second. And 2 is the third. If the specified spawn room does not exist, players will use the normal spawn room.


-------
## START FORCING THROTTLE:
Defines minimum and maximum movement input values for one or more players, possibly forcing or preventing movement.
 - `    PLAYER`:The player or players whose movement will be forced or limited.
 - `    MIN FORWARD`:Sets the minimum run forward amount. O allows the player or players to stop while 1 forces full forward movement.
 - `    MAX FORWARD`:Sets the maximum run forward amount. O prevents the player or players from moving forward while 1 allows full forward movement.
 - `    MIN BACKWARD`:Sets the minimum run backward amount. O allows the player or players to stop while 1 forces full backward movement.


-------
## START HEAL OVER TIME:
Starts an instance of heal over time. This hot will persist for the specified duration or until stopped by script. To obtain a reference to this hot, use the last heal over time id value.
 - `    PLAYER`:One or more players who will receive the heal over time.
 - `    HEALER`:The player who will receive credit for the healing. A healer of null indicates no player will receive credit.
 - `    DURATION`:The duration of the heal over time in seconds. To have a hot that lasts until stopped by script, provide an arbitrarily long duration such as 9999.
 - `    HEALING PER SECOND`:The healing per second for the heal over time.


-------
## START HOLDING BUTTON:
3rces one or more players to hold a button virtually until stopped y the stop holding button action.
 - `    PLAYER`:The player or players who are holding a button virtually.
 - `    BUTTON`:The logical button that is being held virtually.


-------
## STOP ACCELERATING:
Stops the acceleration started by the start accelerating action for one or more players.
 - `    PLAYER`:The player or players who will stop accelerating.


-------
## STOP ALL DAMAGE MODIFICATIONS:
Stops all damage modifications that were started using the start damage modification action.


-------
## STOP ALL DAMAGE OVER TIME:
Stops all damage over time started by start damage over time for one or more players.
 - `    PLAYER`:The player or players whose scripted damage over time will stop.


-------
## STOP ALL HEAL OVER TIME:
Stops all heal over time started by start heal over time for one or more players.
 - `    PLAYER`:The player or players whose scripted heal over time will stop.


-------
## STOP CAMERA:

 - `    PLAYER`:The player or players whose cameras will be put back to the default view.


-------
## STOP CHASING GLOBAL VARIABLE:
Stops an in-progress chase of a global variable, leaving it at its current value.
 - `    VARIABLE`:Specifies which global variable to stop modifying.


-------
## STOP CHASING PLAYER VARIABLE:
Stops an in-progress chase of a player variable, leaving it at its current value.
 - `    PLAYER`:The player whose variable will stop changing. If multiple players ari provided, each of their variables will stop changing.
 - `    VARIABLE`:Specifies which of "-ie player's variables to stop modifying.


-------
## STOP DAMAGE MODIFICATION:
Stops a damage modification that was started by the start damage modification action.
 - `    DAMAGE MODIFICATI!`:Specifies which damage modification instance to stop. This id may be last damage modification id or a variable into which last damage modification id was earlier stored.


-------
## STOP DAMAGE OVER TIME:
Stops an instance of damage over time started by the start damage over time action.
 - `    DAMAGE OVER TIME I\`:Specifies which damage over time instance to stop. This id may be lasi damage over time id or a variable into which last damage over time id was earlier stored.


-------
## STOP FACING:
Stops the turning started by the start facing action for one or more players.
 - `    PLAYER`:The player or players who will stop wrning.


-------
## STOP FORCING PLAYER TO BE HERO:
- stops forcing one or more players to be a specific hero. This will not respawn the player or players, but it will restore their hero availability the next time they go to select a hero.
 - `    PLAYER`:The player or players who will no longer be forced to be a specific hero.


-------
## STOP FORCING SPAWN ROOM:
Undoes the effect of the start forcing spawn room action for the specified team.
 - `    TEAM`:The team that will resume using their normal spawn room.


-------
## STOP FORCING THROTTLE:
Undoes the effect of the start forcing throttle action for one or more players.
 - `    PLAYER`:The player or players whose movement input will be restored.


-------
## STOP HEAL OVER TIME:
Stops an instance of heal over time started by the start heal over time action.
 - `    HEAL OVER TIME ID`:Specifies which heal over time instance to stop. This id may be last heal over time id or a variable into which last heal over time id was earlier stored.


-------
## STOP HOLDING BUTTON:
Undoes the effect of the start holding button action for one or more players.
 - `    PLAYER`:The player or players who are no longer holding a button virtually.
 - `    BUTTON`:The logical button that is no longer being held virtually.


-------
## TELEPORT:
Teleports one or more players to the specified position.
 - `    PLAYER`:The player or players to teleport.
 - `    POSITION`:The position to which the player or players will teleport. If a player is provided, the position of the player is used.


-------
## UNPAUSE MATCH TIME:
Unpauses the match time.


-------
## WAIT:
Auses the execution of the action list. Unless the wait is interrupted, he remainder of the actions will execute after the pause.
 - `    TIME`:The duration of the pause.
 - `    WAIT BEHAVIOR`:Specifies if and how the wait can be interrupted. If the condition list is ignored. The wait will not be interrupted. Otherwise. The condition list will determine if and when the action list will abort or restart.
