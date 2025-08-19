# German Municipal AI Chatbot Dataset

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

## Overview

Dataset documenting AI chatbot implementations across 191 German municipal citizen portals. Manually curated data showing that **14.66%** of municipalities have deployed chatbots.

**Research Paper**: *"Charting the Path Forward: A Research Agenda and Initial Dataset for Public Sector AI Chatbots in Germany"* (forthcoming)

## Dataset

- **File**: `german_municipal_chatbots.csv`
- **Municipalities**: 191
- **Chatbot Adoption**: 14.66%
- **Collection Method**: Manual web analysis

### Key Fields
- Municipality name, population, federal state
- Website URLs (homepage + service portal)
- Chatbot presence indicators
- Implementation type classification

## Usage

```python
import pandas as pd
df = pd.read_csv('german_municipal_chatbots.csv')
print(f"Chatbot adoption rate: {df['Chatbot_vorhanden'].mean():.2%}")
```

## Citation

```bibtex
@article{krueger2025chatbot,
  title={Charting the Path Forward: A Research Agenda and Initial Dataset for Public Sector AI Chatbots in Germany},
  author={Krüger, Nicolai},
  year={2025},
  note={Paper forthcoming}
}
```

## License

CC BY 4.0 - Free to use with attribution

## Author

**Nicolai Krüger**  
University of Applied Sciences for Police and Public Administration in North Rhine-Westphalia, Germany
