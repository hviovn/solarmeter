# solarmeter
New updated solarmeter without the IFTTT service, but using a Cloudflare worker collect the data and store values every two minutes, and finally commit the data to the repository as a pull request to have historic data.

## Related repositories

- [aisvn-data/solarpower](https://github.com/aisvn-data/solarpower) Some tinkering and documenting of early steps in May 2020
- [kreier/solarmeter](https://github.com/kreier/solarmeter) Software repository for the 4 collectors of data 2020-2021
- [aisvn-data/solardata](https://github.com/aisvn-data/solardata) Analyze, clean and display collected solar data.
- [kreier/solar](https://github.com/kreier/solar) Endpoint for different measuring stations and point to visualize historic solar data back to 2020, and temperature data back to 2015 in Hofkoh
