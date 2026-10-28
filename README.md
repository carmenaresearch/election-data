# US election and early-vote data, 2016–2026

Open CSV tables on the 2026 US midterms from [Carmena’s Overton & Electoral Research](https://carmenaresearch.com/): early voting by registered party, county, age and vote history in Kansas, North Carolina, Florida and Iowa; early in-person versus mail ballots; the generic ballot; Senate battleground early-vote pace; and checks on how early-vote trackers are built. Every table is the data behind a published chart and is free to reuse under CC BY 4.0.

Party means voter registration, not vote choice. Comparisons across years are made at the same number of days before Election Day.

## Datasets

| Dataset | What it covers | Files | Updated | Read more |
|---|---|---|---|---|
| [Early In-Person vs Mail Voting 2026, 4 States](data/early-in-person-voting-2026/) | FL, KS, IA, NC early in-person and mail ballots by party, 2022 vs 2026 | 4 | 2026-10-26 | [article](https://carmenaresearch.com/blog/early-in-person-voting-moves-toward-democrats/) · [Kaggle](https://www.kaggle.com/datasets/carmenaresearch/early-in-person-voting-2026) |
| [Early-Vote Tracker Methods: Bias & Checks](data/early-vote-tracker-methods/) | County-lean bias, bellwethers, tracker models and state-record checks, 2016-26 | 7 | 2026-10-23 | [data page](https://carmenaresearch.com/data/) · [Kaggle](https://www.kaggle.com/datasets/carmenaresearch/early-vote-tracker-methods) |
| [Kansas Early Vote 2026: Party, County, History](data/kansas-early-vote-2026/) | Kansas 2026 early ballots by party, county and vote history, vs 2022 and 2024 | 7 | 2026-10-26 | [article](https://carmenaresearch.com/blog/kansas-early-voters-r3-to-d5/) · [Kaggle](https://www.kaggle.com/datasets/carmenaresearch/kansas-early-vote-2026) |
| [North Carolina Early Vote 2026 by Party](data/north-carolina-early-vote-2026/) | NC 2026 early voters by party, county, age, race and vote history, vs 2022 | 10 | 2026-10-26 | [data page](https://carmenaresearch.com/data/) · [Kaggle](https://www.kaggle.com/datasets/carmenaresearch/north-carolina-early-vote-2026) |
| [Reliable Voters’ Early Turnout by Party 2026](data/reliable-voters-early-turnout-2026/) | Four-time voters who voted early, by party and state, 2022 vs 2026 | 5 | 2026-10-27 | [article](https://carmenaresearch.com/blog/reliable-democrats-are-voting-early/) · [Kaggle](https://www.kaggle.com/datasets/carmenaresearch/reliable-voters-early-turnout-2026) |
| [Senate Battlegrounds Early Vote Pace 2026](data/senate-battlegrounds-early-vote-2026/) | Early ballots in ten 2026 Senate battlegrounds vs 2022 and 2024, with party mix | 2 | 2026-10-23 | [data page](https://carmenaresearch.com/data/) · [Kaggle](https://www.kaggle.com/datasets/carmenaresearch/senate-battlegrounds-early-vote-2026) |
| [US Midterm 2026 Indicators: Early Vote, Ballot](data/us-midterm-2026-indicators/) | Generic ballot, early-vote party split and ballots banked, 2026 vs past cycles | 7 | 2026-10-23 | [data page](https://carmenaresearch.com/data/) · [Kaggle](https://www.kaggle.com/datasets/carmenaresearch/us-midterm-2026-indicators) |

Each folder has a README with file and column descriptions, caveats and a citation. [`datapackage.json`](datapackage.json) describes every file and column in the [Frictionless Data](https://specs.frictionlessdata.io/data-package/) format.

## Use the data

```python
import pandas as pd
url = "https://raw.githubusercontent.com/carmenaresearch/election-data/main/data/kansas-early-vote-2026/chart-ks-early-total.csv"
df = pd.read_csv(url)
```

## Licence and citation

[CC BY 4.0](LICENSE). Credit “Carmena’s Overton & Electoral Research” and link to the file or page you used. Figures we quote from other organisations, such as NBC News / TargetSmart, the Silver Bulletin and 538, remain theirs; credit them too. See [CITATION.cff](CITATION.cff) or use GitHub’s “Cite this repository”.

## More from Carmena’s Overton

- Analysis behind these tables: [carmenaresearch.com/blog](https://carmenaresearch.com/blog/) and the [blog-posts](https://github.com/carmenaresearch/blog-posts) repo
- All public data with JSON copies: [carmenaresearch.com/data](https://carmenaresearch.com/data/)
- How we source and check data: [methodology](https://carmenaresearch.com/methodology/)
- New analysis by email: [subscribe](https://carmenaresearch.com/#newsletter)

In-depth data, custom polling and commissioned research are available for commercial use. Non-profits and academic researchers can request access. Write to [queries@carmenaresearch.com](mailto:queries@carmenaresearch.com).
