# German Municipal AI Chatbot Dataset

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.16902154.svg)](https://doi.org/10.5281/zenodo.16902154)

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

## Data Availability

The dataset is permanently archived and citable at:  
**DOI:** [10.5281/zenodo.16902154](https://doi.org/10.5281/zenodo.16902154)

**Why Zenodo?** Zenodo is a research data repository operated by CERN that provides:
- ✅ **Permanent preservation** - guaranteed long-term access
- ✅ **DOI assignment** - makes data scientifically citable
- ✅ **Version control** - tracks dataset updates over time
- ✅ **FAIR principles** - Findable, Accessible, Interoperable, Reusable data

**This GitHub repository** serves as the **working space** for:
- 📊 Data exploration and analysis
- 📄 Paper development and supplementary materials  
- 🤝 Community collaboration and contributions
- 📈 Living documentation and methodology updates

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
