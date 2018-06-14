# Tetration Diagram Exporter

This script allows a user to export policy generated by Tetration into a GraphViz (.dot) file format which can be natively opened by many graphing applications.

* GraphViz (Linux, Windows, Mac) - https://www.graphviz.org
* Microsoft Visio (Windows) with the GraphVisio Plugin - https://bitbucket.org/cowhamr/graphvizio/src
* Omnigraffle (Mac)
* Multiple web tools such as: https://dreampuf.github.io/GraphvizOnline/

# Dependencies

```
pip install tetpyclient pydot terminaltables
```

# Usage

Before using, make sure that you update your Tetration API key in the file tet-diagram.py

```
python tet-diagram.py
```