# Candy analysis for Lidl

Which characteristics drive candy preference, and which new store-brand candy should Lidl prototype?

**Recommendation:** a chocolate bar with a crispy wafer or biscuit centre, tested with and without caramel.

| File | Content |
|---|---|
| `Arpad_Takacs_candy.pptx` | Presentation (5 slides) |
| `candy.ipynb` | Analysis: data, models (ridge regression, fractional logit), validation, results |
| `candy-data.csv` | Data |

## Run

```bash
pip install -r requirements.txt
```

Open `candy.ipynb` and run all cells (about 10 seconds). Fixed random seed; models use only numpy and scipy.

## Data

FiveThirtyEight, [Candy Power Ranking](https://github.com/fivethirtyeight/data/tree/master/candy-power-ranking),
[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Included unchanged.
