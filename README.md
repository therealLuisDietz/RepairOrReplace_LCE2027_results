# To repair or replace? Consumer decision pathways and their influence on the environmental assessments of repairing

Results and figures for the paper presented at the 34th CIRP Conference on Life Cycle Engineering (CIRP LCE 2027).

## Contents

| Folder / file | Content |
|---|---|
| `results/results_lifespan_factor.csv` | Lifespan factor (environmental break-even point) of all 576 repair/replace cases |
| `figures/` | Range plot of all break-even points and the sensitivity analyses (sewing machine, iFixit kit) as PDF, PNG and SVG |
| `data/sewing_machine_LCI.xlsx` | Life cycle inventory, usage and lifespan of the sewing machine |

### Columns of `results_lifespan_factor.csv`

| Column | Description |
|---|---|
| `Product` | Hand blender, smartphone or jeans |
| `Repair Case` | Defect / component that is repaired |
| `Repair Pathway` | Consumer decision pathway for the repair (e.g. self service) |
| `Repair Mode` | Transport mode used within the repair pathway |
| `Repair Transport` | Combined label of repair pathway and transport mode |
| `Replace Transport` | Transport mode used to buy the replacement product |
| `Footprint Base` | `CF` (Carbon Footprint) or `MF` (Material Footprint) |
| `Lifespan Factor` | Break-even point: required lifespan of the repaired product relative to the lifespan of a new product |

## Data availability

This repository contains **only the results**, the figures and the life cycle inventory of the sewing machine. The calculation code and the underlying footprints of the products, spare parts, transport and repair tools are **not** published.

The footprints were calculated with the **ecoinvent** database. The ecoinvent license does not permit publishing these footprints in a form that would allow the underlying ecoinvent datasets (processes) to be traced back or recalculated. They can therefore not be made publicly available.

**Requests for the underlying data should be sent to the corresponding author:**

Jan-Luis Dietz, Wuppertal Institute for Climate, Environment and Energy — jan-luis.dietz@wupperinst.org

## How to cite

```bibtex
@inproceedings{Dietz2027RepairOrReplace,
  author    = {Dietz, Jan-Luis and Bickel, Manuel and Speiser-Tochtrop, Christoph and Zimmermann, Vita E. M.},
  title     = {To repair or replace? Consumer decision pathways and their influence on the environmental assessments of repairing},
  booktitle = {Procedia CIRP, 34th CIRP Conference on Life Cycle Engineering (CIRP LCE 2027)},
  year      = {2027}
}
```

See also [`CITATION.cff`](CITATION.cff).

## License

[Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)](LICENSE)

Use, sharing and adaptation are permitted for non-commercial purposes with attribution. Commercial use is not permitted.
