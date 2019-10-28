# Some commands
To remove jobs from condor:

`condor_rm -name <schedd> <cluster>`

example: `condor_rm -name lpcschedd1.fnal.gov 3905087`

To make histograms from results.root:

`./makePlots -f -I <file> -Y <year> -R Data_MET_<year> | grep -v LHAPDF`
