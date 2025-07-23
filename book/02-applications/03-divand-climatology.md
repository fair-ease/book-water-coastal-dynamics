---
jupytext:
  formats: md:myst
  text_representation:
    extension: .md
    format_name: myst
    format_version: 0.13
    jupytext_version: 1.11.5
kernelspec:
  display_name: Julia 1.11
  language: julia
  name: julia-1.11.6
---

# Creation of a climatology with `DIVAnd`

The main output of a `DIVAnd` workflow is a climatology, i.e. a set of gridded field for a given variable, for instance sea water temperature, at different depth levels and for different time periods.

Different steps are required for the creation of the climatology, from the data extraction to the metadata preparation.

The final output is a netCDF file, the content of which can be visualised with `ODV` (among others) or can be used in `SOURCE`. 

## An example cell

With MyST Markdown, you can define code cells with a directive like so:

```{code-cell}
using DIVAnd
```


```{code-cell} julia
println("hello") 
```
