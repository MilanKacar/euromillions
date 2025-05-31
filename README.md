# Euromillions

Data from **2015–2025** for **Austria**.

Each entry follows this structure:

<pre>
{
  "<b>YYYY-MM-DD</b>": {
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
</pre>

### Notes:

* The top-level key is the **draw date** in format `YYYY-MM-DD`.
* `winning_numbers` are 5 integers between 1 and 50.
* `lucky_stars` are 2 integers between 1 and 12.
* `prizes` is an array of **13 ranks**, from I to XIII.

  * Each rank includes:

    * `rank`: Roman numeral (e.g., "I", "X", "XIII")
    * `combination`: Matching criteria (e.g., "5 Numbers + 2 Stars")
    * `winners`: Number of Austrian winners for that rank
    * `prize`: Prize amount in euros
