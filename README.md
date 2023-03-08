# Low-income building model (EnergyPlus)

This is the low-income building model for EnergyPlus simulation and its user guide.

## Model description

- HVAC systems,
- energy storage,
- controls, including a reference implementation of ASHRAE Standard 231P,
- heat transfer among rooms and the outside, either
  - natively in Modelica with a detailed or a reduced order model, or
  - integrated run-time coupling with EnergyPlus, aka, Spawn of EnergyPlus
- multizone airflow, including natural ventilation and contaminant transport,
- single-zone computational fluid dynamics coupled to heat transfer and HVAC systems,
- data-driven load prediction for demand response applications, and
- electrical DC and AC systems with two- or three-phases that can be balanced and unbalanced.

The main project site is https://bldgict.github.io/.

## License

The Modelica _Buildings_ Library is available under a 3-clause BSD-license.
See [Modelica Buildings Library license](https://htmlpreview.github.io/?https://github.com/lbl-srg/modelica-buildings/blob/master/Buildings/legal.html).

Python modules are available under a 3-clause BSD-license. See [BuildingsPy license](http://simulationresearch.lbl.gov/modelica/buildingspy/legal.html).

## Development and contribution
You may report any issues with using the [Issues](https://github.com/lbl-srg/modelica-buildings/issues) button.

Contributions in the form of [Pull Requests](https://github.com/lbl-srg/modelica-buildings/pulls) are always welcome.
Prior to issuing a pull request, make sure your code follows the [style guide and coding conventions](https://github.com/lbl-srg/modelica-buildings/wiki/Style-Guide).

## Citation

To cite the library, use

Nam, Hye-Ryeong, Seo-Hoon Kim, Seol-Yee Han, Sung-Jin Lee, Won-Hwa Hong, and Jong-Hun Kim.
Statistical methodology for the definition of standard model for energy analysis of residential buildings in Korea.
_Energies_, 13(21), 5796, 2020.

```
@Article{WetterZuoNouiduiPang2014,
  author  =  {Nam, Hye-Ryeong, Seo-Hoon Kim, Seol-Yee Han, Sung-Jin Lee, Won-Hwa Hong, and Jong-Hun Kim},
  title   =  {Statistical methodology for the definition of standard model for energy analysis of residential buildings in Korea},
  journal =  {Energies},
  volume  =  {13},
  number  =  {21},
  pages   =  {5796},
  year    =  {2020},
  doi     =  {10.3390/en13215796},
  url     = "https://doi.org/10.3390/en13215796"
}
```
