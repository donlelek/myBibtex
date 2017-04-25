# myBibtex

A bibtex file with curated references I frequently use.

Based on [this post](http://serialmentor.com/blog/2015/10/2/Bibtex), I modified my references accordingly. I put special attention into avoiding the following mistakes:

- Incorrectly capitalized article titles (protect capital letters with curly braces)
- Incorrectly abbreviated first names and missing middle initials (replaced first and middle names with their initial followed by a period)
- Inconsistent journal names (looked for proper abbreviations and added periods after abbreviated words)
- Superfluous issue numbers, publication months, or other elements (for article I only kept the `title`, `author`, `journal`, `volume`, `pages`, `year`, and `doi` fields)

Additionally, I replaced all special characters with their latex-code, thus an `é` became `\{'e}` and an `ø` became `\{\o}` and so on.

Example:

```
@article{Price2016,
  title={Retrospective analysis of antibiotic treatments against piscirickettsiosis in farmed Atlantic salmon Salmo salar in Chile.},
  author={Price, D. and Stryhn, H. and S{\'a}nchez, J. and Ibarra, R. and Tello, A. and {St-Hilaire,} S.},
  journal={Dis. Aquat. Org.},
  volume={118},
  pages={227-235},
  year={2016},
  doi={10.3354/dao02978}
}
```