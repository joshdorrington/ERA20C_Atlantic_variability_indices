# ERA20C Atlantic variability_indices
This is a repository for jet and circulation regime indices used in Dorrington &amp; Strommen 2020 (doi:10.1029/2020GL087907), that may be of interest to anyone wishing to reproduce or extend those results.

The csv file contains a range of indices for Boreal winter (DJF) from 1900 until 2010, calculated from the ERA20C reanalysis (Poli et al. 2016, doi:10.1175/JCLI-D-15-0556.1).

* The __date__ column contains the day and time for which each index is valid. For jet indices which are calculated with a 9-day smoothing window, this is the central day.
* The __t__ column is another representation of the date and time expressed as hours since 1900/01/01 00:00.
* The __jet_lat__ column contains the latitude for which zonal wind speed in the Euroatlantic sector was highest, calculated on a 2.5 degree grid.
* The __jet_speed__ column contains the zonal wind speed zonally averaged across the Euroatlantic sector at the latitude of __jet_lat__.
* The __U4_regnum__ and __U4regname__ columns contain the assignment of each day in the record to one of 4 circulation regimes, calculated using raw PCs of Z500 anomalies.
* Likewise, the __R3/5_regnum__ and __R3/5regname__ columns contain the assignment of each day to one of 3 or 5 regimes respectively, calculated in residual PCs of Z500 anomalies.

For more detail on these indices see Dorrington & Strommen 2020, and references therein.

If you notice any problems or errors with this data, please feel free to contact joshua.dorrington@physics.ox.ac.uk
