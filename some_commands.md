# Some commands

|description|syntax|example|
|:--|:--|:--|
| remove jobs from condor | `condor_rm -name <schedd> <cluster>` | `condor_rm -name lpcschedd1.fnal.gov 3905087` |
| make histograms from results.root | `./makePlots -f -I <file> -Y <year> -R Data_MET_<year> | grep -v LHAPDF` |  |
| activate voms | `voms-proxy-init --valid 168:00 -voms cms` |  |
| push branch to remote | `git push <remote>  <local branch>:<new remote branch>` |`git push origin master:devbranch`  |
| vim multiple word search | `/\vword1|word2|word3` |  `/\vLoose|Mid` |
| enable Jupyter |`ssh ... -L 8yyy:localhost:8yyy`  | substitute yyy with a three digits number |
|  open Jupyter notebook| `jupyter notebook --no-browser --port 8yyy` | substitute yyy with the three digits number |

# Python related

- [Reading and Writing JSON to a File in Python](https://stackabuse.com/reading-and-writing-json-to-a-file-in-python/)
- [What does if \_\_name\_\_ == "\_\_main\_\_": do?](https://stackoverflow.com/questions/419163/what-does-if-name-main-do)

# Bash related

- [How to use arrays in bash script](https://linuxconfig.org/how-to-use-arrays-in-bash-script)
- [Process Substitution](http://mywiki.wooledge.org/ProcessSubstitution)
- [process substitution are not waited](https://unix.stackexchange.com/questions/403783/the-process-substitution-output-is-out-of-the-order)
- [Long bash command in multiple lines](https://superuser.com/questions/508507/linux-bash-script-single-command-but-multiple-lines)
- [Never say "If" writing a Bash script!](https://www.youtube.com/watch?v=p0KKBmfiVl0)

# LaTex related

- [.cls and .sty files](https://tug.org/pracjourn/2005-3/asknelly/nelly-sty-&-cls.pdf)
- [catch file between tags](https://texblog.org/2012/12/04/keeping-things-organized-in-large-documents/)
