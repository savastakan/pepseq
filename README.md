# PepSeq: a Novel Algorithm for Accurate De Novo Sequencing of Tandem Mass Spectra

Table 1: Possible fragmentation edges.

| Ion 1 | Ion 2 | Edge label | Difference in Dalton (z = 1) | Node Type                    |
|-------|-------|------------|------------------------------|------------------------------|
| a     | b-H2O | ɘ10        | 10                           | N-terminal with neutral loss |
| a     | b-NH3 | ɘ11        | 11                           | N-terminal with neutral loss |
| a-NH3 | b-H2O | ɘ27        | 27                           | N-terminal with neutral loss |
| a     | b     | ɘ28        | 28                           | N-terminal                   |
| a-H2O | b-NH3 | ɘ29        | 29                           | N-terminal with neutral loss |
| b-NH3 | c     | ɘ34        | 34                           | N-terminal with neutral loss |
| b-H2O | c     | ɘ35        | 35                           | N-terminal with neutral loss |
| a     | c     | ɘ45        | 45                           | N-terminal                   |
| a-NH3 | b     | ɘ45        | 45                           | N-terminal with neutral loss |
| a-H2O | b     | ɘ46        | 46                           | N-terminal with neutral loss |
| a-NH3 | c     | ɘ62        | 62                           | N-terminal with neutral loss |
| a-H2O | c     | ɘ63        | 63                           | N-terminal with neutral loss |
| b     | c     | ɘ17        | 17                           | N-terminal                   |
| -NH3  |       | ɘ17        | 17                           | Neutral loss                 |
| -H2O  |       | ɘ18        | 18                           | Neutral loss                 |
| y-NH3 | z     | ɘ1         | 1                            | C-terminal with neutral loss |
| y-H2O | z     | ɘ2         | 2                            | C-terminal with neutral loss |
| y     | x     | ɘ26        | 26                           | C-terminal                   |
| z     | x     | ɘ43        | 43                           | C-terminal                   |
| y-NH3 | x     | ɘ44        | 44                           | C-terminal with neutral loss |
| y-H2O | x     | ɘ45        | 45                           | C-terminal with neutral loss |

Table 2: Possible amino acid edges. Some amino acids are very similar in mass and may not be differentiated depending on the instrument error. These are grouped and an example grouping for ɛ = 0.5 is given in the table below.

| Amino acid    | Edge Label | Group label | Monoisotopic mass |
|---------------|------------|-------------|-------------------|
| Glycine       | ɘG         |             | 57.021674         |
| Alanine       | ɘA         |             | 71.037474         |
| Serine        | ɘS         |             | 87.032374         |
| Proline       | ɘP         |             | 97.053274         |
| Valine        | ɘV         |             | 99.069074         |
| Threonine     | ɘT         |             | 101.048174        |
| Cysteine      | ɘC         |             | 103.009574        |
| Leucine       | ɘJ         |             | 113.084874        |
| Isoleucine    | ɘJ         |             | 113.084874        |
| Asparagine    | ɘN         |             | 114.043348        |
| Aspartic acid | ɘD         |             | 115.027274        |
| Glutamine     | ɘQ         |             | 128.059148        |
| Lysine        | ɘK         |             | 128.095848        |
| Glutamic acid | ɘE         |             | 129.043074        |
| Methionine    | ɘM         |             | 131.041174        |
| Histidine     | ɘH         |             | 137.059422        |
| Phenylalanine | ɘF         |             | 147.069074        |
| Arginine      | ɘR         |             | 156.101996        |
| Tyrosine      | ɘY         |             | 163.063974        |
| Tryptophan    | ɘW         |             | 186.080048        |

