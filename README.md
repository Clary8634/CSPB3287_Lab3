# CSPB3287_Lab3

Relationships:
------------------------

Player & Team:
  Many to One
  A team has multiple players, but a player may only belong to one team.

Team & Game:
  Many to Many
  Each game will have two teams, and a team may play many games.

Play & Game:
  Many to One
  A game will have multiple plays, but each play will belong to one game.

Play & Run/Pass Play:
  One to One
  Each play is either a running or passing play, this can be evidenced via the unique Play ID.

Player & RunPlay:
  One to Many
  A player may be only involved once in a running play, but may participate in multiple plays.

Player & Pass Play:
  One to Many
  A player may be only involved once in a passing play, but may participate in multiple plays.
