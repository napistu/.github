# Napistu

**Genome-Scale Mechanistic Networks for Biological Pathway Analysis**

Napistu is an open-source project for creating and mining genome-scale networks of cellular physiology. Build consensus pathway models from diverse data sources, analyze biological networks, and train graph neural networks to predict regulatory interactions.

## 🔬 What is Napistu?

- **Unified Representation** - Encode diverse data sources using the `sbml_dfs` structure to faithfully represent molecular biology and biochemistry
- **Consensus Models** - Aggregate complementary sources into comprehensive networks where high-quality but incomplete interactions are supported by more comprehensive yet speculative data sources
- **Network Analysis** - Translate pathway models into genome-scale graphical networks for propagation, search, and neighborhood discovery
- **Machine Learning** - Train graph neural networks on biological networks to predict regulatory interactions and pathway relationships
- **Easy Access** - Pre-processed pathway data available on Google Cloud Storage and HuggingFace; MCP server for AI agent integration

## 📦 Core Packages

### [napistu-py](https://github.com/napistu/napistu-py)
Core Python library for pathway representations and network-based searches.

[![PyPI](https://badge.fury.io/py/napistu.svg)](https://pypi.org/project/napistu/)
[![Documentation](https://readthedocs.org/projects/napistu/badge/?version=latest)](https://napistu.readthedocs.io/)

```bash
pip install napistu
```

### [napistu-torch](https://github.com/napistu/napistu-torch)
PyTorch Geometric framework for training GNNs on biological pathways.

[![PyPI](https://badge.fury.io/py/napistu-torch.svg)](https://pypi.org/project/napistu-torch/)
[![Documentation](https://readthedocs.org/projects/napistu-torch/badge/?version=latest)](https://napistu-torch.readthedocs.io/)

```bash
pip install 'napistu-torch[pyg,lightning]'
```

### [napistu-r](https://github.com/napistu/napistu-r)
R library for network visualization and utilities.

[![pkgdown](https://github.com/napistu/napistu-r/actions/workflows/pkgdown.yaml/badge.svg)](https://napistu.github.io/napistu-r/)

```r
remotes::install_github("napistu/napistu-r")
```

## 📚 Resources

- **[Website](https://napistu.com)** - Project landing page
- **[Tutorials](https://github.com/napistu/napistu)** - Examples and documentation
- **[Wiki](https://github.com/napistu/napistu/wiki)** - Core algorithms and data structures
- **[Blog](https://www.shackett.org/)** - Deep dives and tutorials
- **[HuggingFace](https://huggingface.co/Napistu)** - Pre-trained models and datasets

## 📖 Recent Blog Posts

- [Napistu meets PyTorch Geometric - Predicting Regulatory Interactions with GNNs](https://www.shackett.org/napistu_torch/) (Nov 2025)
- [Napistu's Octopus: An 8-source human consensus pathway model](https://www.shackett.org/octopus_network/) (Oct 2025)
- [Building AI-Friendly Scientific Software: A Model Context Protocol Journey](https://www.shackett.org/napistu_mcp/) (Sep 2025)

## 💬 Get Help

- **Issues** - [GitHub Issues](https://github.com/napistu/napistu/issues)
- **Chat** - Visit [napistu.com](https://napistu.com) for interactive AI assistan
