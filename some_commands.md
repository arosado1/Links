# Some commands
To remove jobs on condor:

`condor_rm -name <schedd> <cluster>`

e.g. condor_rm -name lpcschedd1.fnal.gov 3905087

To make histograms from results.root:

`./makePlots -f -I <file> -Y <year> -R Data_MET_<year> | grep -v LHAPDF`
