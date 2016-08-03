# risk-graph
Topology (graph) of Risk(tm) game countries and continents


Using the original Risk(tm) map found here:
<img src="https://wargamingmiscellanybackup.files.wordpress.com/2011/09/cimg3372.jpg">

Using graphviz:

`ccomps -x risk.dot | dot | gvpack -array_u | neato -Tpng -n2 -o risk.png`

<img src="https://gnewton.github.io/repos/risk-graph/risk.svg">
