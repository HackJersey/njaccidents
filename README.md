# njaccidents
Makefile for combining NJ [accident data](http://www.state.nj.us/transportation/refdata/accident/) from the state Department of Transportation into one massive CSV.

Currently, this grabs data from the [accident tables](http://www.state.nj.us/transportation/refdata/accident/master.shtm) for 2008-2014. It does not handle the [driver](http://www.state.nj.us/transportation/refdata/accident/drivers.shtm), [vehicle](http://www.state.nj.us/transportation/refdata/accident/vehicles.shtm), [pedestrian](http://www.state.nj.us/transportation/refdata/accident/pedestrians.shtm) or [occupant](http://www.state.nj.us/transportation/refdata/accident/occupants.shtm) tables.

```
git clone https://github.com/tommeagher/njaccidents.git
make dl
make unzip
make cat
```
