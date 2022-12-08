Template:
<b><font color="#E44138">Problem:</font></b> 
<b><font color="#6ED7D9">Solution:</font></b> 


<b><font color="#E44138">Problem:</font></b> no module named serene

<b><font color="#6ED7D9">Solution:</font></b> 
```
import sys
sys.path.insert(0, '../') // inserts the previous directory to path
						  // (not a gaurnteed solution -- may work)
```

<b><font color="#E44138">Problem:</font></b> module 'collections' has no attribute 'MutableSequence'
<b><font color="#6ED7D9">Solution:</font></b>  change `collections.MutableSequence` to `collections.abc.MutableSequence`

*Reason: collections.MutableSequence was depreciated*

<b><font color="#E44138">Problem:</font></b> No module named 'rdflib'
<b><font color="#6ED7D9">Solution:</font></b> pip installed rdflib

<b><font color="#E44138">Problem:</font></b>  No module named 'networkx'
<b><font color="#6ED7D9">Solution:</font></b>  pip installed networkx

<b><font color="#E44138">Problem:</font></b> ModuleNotFoundError: No module named 'pygraphviz'
<b><font color="#6ED7D9">Solution:</font></b>  pip installed pygraphviz

<b><font color="#E44138">Problem:</font></b>  fatal error: 'graphviz/cgraph.h' file not found
<b><font color="#6ED7D9">Solution:</font></b> install using the following command (only for m1 macs)
````python
pip install --global-option=build_ext --global-option="-I/opt/homebrew/include/graphviz" --global-option="-L/opt/homebrew/Cellar/graphviz/2.46.1/lib/"  pygraphviz
````

<b><font color="#E44138">Problem:</font></b> 
<b><font color="#6ED7D9">Solution:</font></b> 

<b><font color="#E44138">Problem:</font></b> 
<b><font color="#6ED7D9">Solution:</font></b> 

<b><font color="#E44138">Problem:</font></b> 
<b><font color="#6ED7D9">Solution:</font></b> 

<b><font color="#E44138">Problem:</font></b> 
<b><font color="#6ED7D9">Solution:</font></b> 

<b><font color="#E44138">Problem:</font></b> 
<b><font color="#6ED7D9">Solution:</font></b> 

<b><font color="#E44138">Problem:</font></b> 
<b><font color="#6ED7D9">Solution:</font></b> 

<b><font color="#E44138">Problem:</font></b> 
<b><font color="#6ED7D9">Solution:</font></b> 

<b><font color="#E44138">Problem:</font></b> 
<b><font color="#6ED7D9">Solution:</font></b> 
