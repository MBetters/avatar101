# Resource Description Framework (RDF)
- [System Resource](https://en.wikipedia.org/wiki/System_resource)
    - A physical or virtual object in a system
- [Semantic Triple](https://en.wikipedia.org/wiki/Semantic_triple)
    - A statement about a resource, in the form `Subject-Predicate-Object`
    - Typical visualization

![Alt text](https://g.gravizo.com/svg?digraph G {
aize="4,4";
main[shape=box];
main->parse[weight=8];
parse->execute;
main->init[style=dotted];
main->cleanup;
execute->{make_string;printf}
init->make_string;
edge[color=red];
main->printf[style=bold,label="100%20times"];
make_string[label="make%20a%20string"];
node[shape=box,style=filled,color=".7%20.3%201.0"];
execute->compare;
})

# Namespaces
- [Example Industry Standard Namespace](http://www.w3.org/2001/XMLSchema#)
- [Example Unimplemented Namespace](http://www.cubrc.org/avatar#)


