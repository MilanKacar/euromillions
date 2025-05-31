# Euromillions

Data from 2015-2025 for Austria.

Data has following structure:

{
  "YYYY-MM-DD": {
    "winning_numbers": [int, int, int, int, int],        // 5 main numbers drawn (1–50)
    "lucky_stars": [int, int],                           // 2 lucky stars drawn (1–12)
    "prizes": [
      {
        "rank": "I",                                     // Prize tier (Roman numeral)
        "combination": "5 Numbers + 2 Stars",            // Description of the matching combination
        "winners": int,                                  // Number of winners in Austria
        "prize": float                                   // Prize amount in euros
      },
      {
        "rank": "II",
        "combination": "5 Numbers + 1 Star",
        "winners": int,
        "prize": float
      },
      {
        "rank": "III",
        "combination": "5 Numbers + 0 Stars",
        "winners": int,
        "prize": float
      },
      {
        "rank": "IV",
        "combination": "4 Numbers + 2 Stars",
        "winners": int,
        "prize": float
      },
      {
        "rank": "V",
        "combination": "4 Numbers + 1 Star",
        "winners": int,
        "prize": float
      },
      {
        "rank": "VI",
        "combination": "4 Numbers + 0 Stars",
        "winners": int,
        "prize": float
      },
      {
        "rank": "VII",
        "combination": "3 Numbers + 2 Stars",
        "winners": int,
        "prize": float
      },
      {
        "rank": "VIII",
        "combination": "2 Numbers + 2 Stars",
        "winners": int,
        "prize": float
      },
      {
        "rank": "IX",
        "combination": "3 Numbers + 1 Star",
        "winners": int,
        "prize": float
      },
      {
        "rank": "X",
        "combination": "3 Numbers + 0 Stars",
        "winners": int,
        "prize": float
      },
      {
        "rank": "XI",
        "combination": "1 Number + 2 Stars",
        "winners": int,
        "prize": float
      },
      {
        "rank": "XII",
        "combination": "2 Numbers + 1 Star",
        "winners": int,
        "prize": float
      },
      {
        "rank": "XIII",
        "combination": "2 Numbers + 0 Stars",
        "winners": int,
        "prize": float
      }
    ]
  }
}

