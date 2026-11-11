# Data Dictionary

## CharlesBookClub.csv
4,000 customers. Source: adapted with permission from *The Bookbinders Club*, prepared by Nissan Levin and Jacob Zahavi.

| Variable | Description |
|---|---|
| `Seq#` | Sequence number in the sample |
| `ID#` | ID in the full dataset |
| `Gender` | 0 = male, 1 = female |
| `M` | Monetary: total money spent on books |
| `R` | Recency: months since last purchase |
| `F` | Frequency: total number of purchases |
| `FirstPurch` | Months since first purchase |
| `ChildBks`, `YouthBks`, `CookBks`, `DoItYBks`, `RefBks`, `ArtBks`, `GeogBks`, `ItalCook`, `ItalAtlas`, `ItalArt`, `Florence` | Number of books purchased in each category (children's, youth, cooking, do-it-yourself, reference, art, geography, Italian cooking, Italian atlas, Italian art, art history of Florence) |
| `Related Purchase` | Number of related books purchased |
| `Mcode`, `Rcode`, `Fcode` | Recoding of M, R and F (see the case description in *DMBA*) |
| `Yes_Florence`, `No_Florence` | One-hot flags for whether the customer purchased the Florence title |

## Faceplate.csv
Synthetic data on purchases of phone faceplates (10 transactions; one 0/1 column per colour: Red, White, Blue, Orange, Green, Yellow). © 2016 Galit Shmueli and Peter Bruce.
