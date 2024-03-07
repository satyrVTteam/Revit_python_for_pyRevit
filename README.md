Most used scripts for Revit_python ported for pyRevit due to death of "Dyno Browser" shell.
Tested with Revit 2024 and pyRevit v4.8.14
No extra dynamo packages required.
All the python script nodes are switched to CPython3 with exceptions:
1. You still have to install IronPython2.7 to make Data-Shapes UI windows work. 
2. Don't switch pop-up python scripts to CPython3 because there is a bug in Dynamo "TaskDialog."
Feel free to edit the source .dyn script for your needs.
