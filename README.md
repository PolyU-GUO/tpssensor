# Raw calibration data of single-point-type tactile pressure sensors (TPS)

Raw experimental data supporting the article:

> Guo, C. and Zhou, C. (2025). *Novel Single-Point-Type Tactile Pressure Sensors for Earth and
> Soil-Structure Interface Contact Pressures Measurement.* **Geotechnical Testing Journal** 48(5):
> 728-746. https://doi.org/10.1520/GTJ20240066

The data are the post-installation calibration records of 18 TPS-based sensors — 15 TPS-ICPT
(soil-structure interface contact pressure transducers) and 3 TPS-EPC (earth pressure cells),
labelled **101-118**. Sensors were calibrated in a sealed pressure tank: the pressure was raised
stepwise from 0 kPa to a maximum calibration pressure (60, 100 or 200 kPa) and then released back
to 0 kPa, at a loading rate of 4 kPa/min. Each sensor output is its electrical resistance *R*
(Ohm); the electrical conductance *G* = 1/*R* is the quantity used for the pressure conversion in
the article.

## Files

| File | Description |
| --- | --- |
| `Series A.xlsx` | Calibration records of the 18 sensors |
| `Series B.xlsx` | Same workbook structure as Series A (contains one extra blank sheet) |
| `Guo-2025-Novel Single-Point-Type Tactile Press.pdf` | The method article: sensor design, signal processing and calibration (GTJ, copyright ASTM International) |

The following three articles apply this TPS measurement technique in physical model tests; they are
included as application references:

| File | Description |
| --- | --- |
| `Guo-2024-Axial behaviour of steel pipelines bu.pdf` | Axial behaviour of steel pipelines buried in sand — effects of surface roughness and hardness (Géotechnique) |
| `Guo-2025-Cyclic and post-cyclic axial behavior.pdf` | Cyclic and post-cyclic axial behaviours of steel pipelines buried in dense sand (Acta Geotechnica) |
| `Guo-2025-Axial Behaviour of Underground Steel.pdf` | Axial behaviour of underground steel pipeline buried in unsaturated soils (Tunnelling and Underground Space Technology) |

## Related publications (applications of the technique)

* Guo, C. and Zhou, C. (2025). Axial Behaviour of Steel Pipelines Buried in Sand: Effects of Surface
  Roughness and Hardness. *Géotechnique* 75(6): 800-813. https://doi.org/10.1680/jgeot.24.00001
* Guo, C., Zhou, C. and Meguid, M. A. (2026). Cyclic and Post-cyclic Axial Behaviors of Steel
  Pipelines Buried in Dense Sand. *Acta Geotechnica* 21: 823-842.
  https://doi.org/10.1007/s11440-025-02790-w
* Guo, C. and Zhou, C. (2025). Axial Behaviour of Underground Steel Pipeline Buried in Unsaturated
  Soils. *Tunnelling and Underground Space Technology* 164: 106831.
  https://doi.org/10.1016/j.tust.2025.106831

## Workbook layout

Both workbooks have the same layout:

* **`Sheet1`** — the original continuous records of three calibration loops, arranged side by side.
  Each loop runs 0 kPa → maximum pressure → 0 kPa; the three blocks correspond to maximum
  calibration pressures of 100, 200 and 60 kPa.
* **`{Pmax} loading` / `{Pmax} unloading` / `{Pmax} both`** (`Pmax` = 60, 100, 200 kPa) — the same
  records separated into the loading path, the unloading path, and the loop path (`both`, i.e. the
  mean of the loading and unloading readings at each pressure level). Each sheet holds three
  repeated calibrations.
* **`Sheet11`** — non-linearity error of each sensor for the three maximum calibration pressures
  and the three paths (`l` = loading, `u` = unloading, `b` = loop), i.e. the data plotted in
  Fig. 5A of the article. Values are dimensionless ratios (×100 gives %); the last row is the
  average over the 18 sensors.

Columns are `P` — applied pressure (kPa) — followed by the resistance of each sensor,
`101R (Ohm)` … `118R (Ohm)`.

Note: the numerical contents of `Series A.xlsx` and `Series B.xlsx` are identical as uploaded; if
the two series are meant to represent different test conditions, please refer to the article for
the distinction.

## License

The data files are shared under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) — see
[LICENSE.md](LICENSE.md). When using the data, please cite the article above.

## Contact

Chang Guo — The Hong Kong Polytechnic University (GitHub: [PolyU-GUO](https://github.com/PolyU-GUO))
