
# YouTube Channel and Video Analysis

A Python data-analysis project exploring publicly available YouTube channel and video statistics using the YouTube Data API v3.

## Research Questions

- How do selected YouTube channels differ in subscriber counts, total views, and number of uploaded videos?
- Which videos on a selected channel have the highest view counts?
- How are a channel's uploads distributed across calendar months?

## Methods

- Collecting public channel and video metadata through the YouTube Data API
- Cleaning and analyzing tabular data with Pandas
- Comparing channel statistics using Seaborn and Matplotlib
- Identifying highly viewed videos
- Exploring monthly upload patterns

## Repository Contents

- `YouTube_Channel_Analysis.ipynb` — the main notebook containing data collection, analysis, and visualizations.

## Setup

Install Python and Jupyter Notebook, then install the required libraries:

```bash
pip install pandas matplotlib seaborn google-api-python-client jupyter
```

Set your YouTube API key as an environment variable. Never place a real API key in a notebook or commit it to GitHub.

**macOS/Linux:**

```bash
export YOUTUBE_API_KEY="YOUR_API_KEY"
jupyter notebook
```

**Windows PowerShell:**

```powershell
$env:YOUTUBE_API_KEY = "YOUR_API_KEY"
jupyter notebook
```

Open `YouTube_Channel_Analysis.ipynb` and run the notebook from top to bottom.

## Limitations

- The notebook uses live API data, so results change over time.
- The selected channels are not a representative sample of YouTube.
- Views and engagement are influenced by many factors. This descriptive analysis does not establish causality.
- API quotas and access permissions may affect data collection.

The notebook has been cleaned to read the API key from an environment variable. It has not yet been validated end-to-end against the live API.

## Technologies

Python · YouTube Data API v3 · Pandas · Seaborn · Matplotlib · Jupyter Notebook
