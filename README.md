# Automated knowledge extraction from polymer literature

This repo contains starter code and data for the paper 'Automated knowledge extraction from polymer literature using Natural Language Processing' [1](https://www.sciencedirect.com/science/article/pii/S2589004220311196). If you use the code or data in this repo, please cite the paper using the bibtex reference below.

```
@article{shetty2021automated,
  title={Automated knowledge extraction from polymer literature using natural language processing},
  author={Shetty, Pranav and Ramprasad, Rampi},
  journal={Iscience},
  volume={24},
  number={1},
  pages={101922},
  year={2021},
  publisher={Elsevier}
}
```

## Requirements and Setup

- Python 3.6+
- Gensim (tested with version 3.8.0)
- Numpy (tested with version 1.17.4)
- Chemdataextractor (tested with version 1.3.0)

You can install all required Python packages with `pip install -r requirements.txt`

## Running IPython Notebook Demo

The Word2Vec model described in the paper can be found at 10.6084/m9.figshare.13211015. The notebook contains starter code to access the word vector model and replicate some of the experiments from the paper such as computing nearest neighbors in word vector space and computing analogies.

## References

[1] Shetty, Pranav, and Rampi Ramprasad. "Automated knowledge extraction from polymer literature using natural language processing." Iscience 24.1 (2021): 101922.
