# citation-signal-network

Citation logger, paper signaling, research impact tracking, and academic intelligence network.

## Features

- **Citation logging**: Track and manage paper citations automatically
- **Paper signaling**: Discover trending and influential research
- **Impact tracking**: Monitor research impact metrics over time
- **Academic intelligence**: Network analysis of research communities
- **Multi-source**: Integrates with Semantic Scholar, CrossRef, and PubMed

## Installation

```bash
pip install -r requirements.txt
```

## Project Structure

```
src/
├── signals/        # Citation signaling and impact analysis modules
examples/           # Usage examples and notebooks
```

## Quick Start

```python
from src.signals.citation_tracker import CitationTracker

tracker = CitationTracker()
citations = tracker.get_citations("paper_doi_here")
impact = tracker.compute_impact_score(citations)
```

## License

MIT
