---
title: Grouped summaries
---

<!-- Generated automatically from vis-summaries.yml. Do not edit by hand -->

# Grouped summaries
<small>(Builds on: [The grammar of graphics](vis-theory.md))</small>

Summary functions take a vector of data and return a single number; you use them in conjunction with `dplyr::summarise()`. The ggplot2 equivalent are the summary geoms, which the data into pieces, apply some summary and visualise the results.
Summaries are useful when you have a lot of data (and plotting leads to overplotting), or when the data is noisy (and you need to make small but consistent patterns more clear).

## Readings

  * [Toolbox](http://link.springer.com.ezproxy.stanford.edu/chapter/10.1007/978-3-319-24277-4_3) [ggplot2-3].
    Read only §3.5: summary geoms are a special case of compound geoms that do
    some aggregation before visualising the data.



