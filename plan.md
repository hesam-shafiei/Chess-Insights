1. overview:
int total_games_played
int num_games_won
int num_games_lost
int num_games_drawn


2. Results by opponent rating
{
100-199: {
   int games_won
   int games_lost
   int games_drawn
},
200-299:{
   int games_won
   int games_lost
   int games_drawn
}
... and so on untill 3300+
}


3. Game Results
won_by: {
  int resignation
  int checkmate
  int timeout
  int abandonment
}
drew_by: {
   int agreement
   int stalemate
   int 50 move rule
   int insufficient material
   int timeout vs insufficient material
   int repetition
}
lost_by: {
  int resignation
  int checkmate
  int abandonment
  int timeout
}
