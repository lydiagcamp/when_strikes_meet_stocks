# When Strikes Meet Stocks: The Complex Interplay Between Organized Labor and Employee Stock Ownership

**Lydia Camp**  
[`https://lydiagcamp.github.io`](https://lydiagcamp.github.io)

This repository contains the data and replication code for a paper examining the effect of union strength on employee stock ownership plan (ESOP) adoption. Using a staggered difference-in-differences design, the paper estimates the causal impact of right-to-work (RTW) laws on union strength and ESOP formation across U.S. states.

## Replication Materials
- **Full Paper**  
  [`Read the paper here!`](https://github.com/lydiagcamp/when_strikes_meet_stocks/raw/main/Final_Paper.pdf)

- **Replication Code**  
  [`https://lydiagcamp.github.io/when_strikes_meet_stocks/`](https://lydiagcamp.github.io/when_strikes_meet_stocks/)

- **Interactive Map of ESOPs Across the U.S.**  
  [`Open the map here!`](https://lydia-camp.shinyapps.io/plans-map-us/)


## Variables

| Variable | Description |
|--------|------------|
| `state_id` | State identifier |
| `state` | State abbreviation |
| `year` | Observation year |
| `union_density` | Percent of workers unionized |
| `num_strikes` | Number of work stoppages |
| `left_wing` | Left-wing government indicator |
| `state_pop` | State population |
| `manufact` | Manufacturing employment |
| `real_median_in` | Real median income |
| `num_firms` | Number of firms |
| `manufact_per` | Manufacturing share of employment |
| `rtw` | Right-to-work law indicator |
| `rtw_year` | Year RTW law enacted |
| `ln_state_pop` | Log state population |
| `ln_manufact` | Log manufacturing employment |
| `ln_num_firms` | Log number of firms |
| `ln_real_median_in` | Log real median income |
| `num_esops_form_5500` | ESOPs filed (Form 5500) |



## Additional Resources on Staggered & Instrumented Difference-in-Differences

For readers interested in modern staggered difference-in-differences approaches, the following resources provide helpful tutorials, documentation, and methodological background:

- **Applied R tutorial (Callaway–Sant’Anna DiD)**  
  *Staggered Difference-in-Differences in R*  
  https://rpubs.com/mbounthavong/cs_staggered_did_r

- **`did` R package documentation**  
  Callaway & Sant’Anna (2021)  
  https://bcallaway11.github.io/did/

- **`twfeivdecomp` R package documentation**  
  Instrumented Difference-in-Differences Decomposition  
  <https://cran.r-project.org/web/packages/twfeivdecomp/twfeivdecomp.pdf>

- **Methodological reference**  
  Callaway, B., & Sant’Anna, P. H. C. (2021).  
  *Difference-in-Differences with Multiple Time Periods*.  
  Journal of Econometrics.  
  https://doi.org/10.1016/j.jeconom.2020.12.001
