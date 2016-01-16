# njaccidents
Makefile for combining NJ [accident data](http://www.state.nj.us/transportation/refdata/accident/) from the state Department of Transportation into one massive CSV.

Currently, this grabs data from the [accident tables](http://www.state.nj.us/transportation/refdata/accident/master.shtm) for 2008-2014. It does not handle the [driver](http://www.state.nj.us/transportation/refdata/accident/drivers.shtm), [vehicle](http://www.state.nj.us/transportation/refdata/accident/vehicles.shtm), [pedestrian](http://www.state.nj.us/transportation/refdata/accident/pedestrians.shtm) or [occupant](http://www.state.nj.us/transportation/refdata/accident/occupants.shtm) tables.

This works only on Unix (Mac) or Linux machines with make installed. It may work on a Windows machine with a Unix-like environment, such as [Cygwin](https://www.cygwin.com/). You'll also need to have [git](https://git-scm.com/) installed to make this work. Then, just create a directory in your terminal and follow these steps:

```
git clone https://github.com/tommeagher/njaccidents.git
make dl
make unzip
make cat
```
