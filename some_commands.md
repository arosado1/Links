# Some commands

|description|syntax|example|
|:--|:--|:--|
| remove jobs from condor | `condor_rm -name <schedd> <cluster>` | `condor_rm -name lpcschedd1.fnal.gov 3905087` |
| make histograms from results.root | `./makePlots -f -I <file> -Y <year> -R Data_MET_<year> \| grep -v LHAPDF` | |
| activate voms | `voms-proxy-init --valid 168:00 -voms cms` | |
| push branch to remote | `git push <remote>  <local branch>:<new remote branch>` |`git push origin master:devbranch`  |
<col width="70%" />

# Python related

- [Reading and Writing JSON to a File in Python](https://stackabuse.com/reading-and-writing-json-to-a-file-in-python/)
