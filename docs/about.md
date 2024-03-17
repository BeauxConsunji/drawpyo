# Conventions and Naming

This library contains quite a lot of camel case (capitalizeEachWord) attributes. While the Python convention is snake case (underscores_between_lowercase) the Draw.io style strings and attributes are camel case. Wherever possible, drawpyo uses the terminology and variable names from Draw.io to make it more intuitive to work between the two apps. However, any attribute that does not have an analogy in the Draw.io app is snake case. While this is a bit confusing I hope it helps to clarify when there's a direct analog between drawpyo and Draw.io and when the variable is a drawpyo abstraction. If this is confusing please share that feedback on the GitHub page or email and it may be changed in future versions!

# Basic Diagrams

Drawpyo's basic functionality provides the same features as using the Draw.io app. You can create files with one or more pages, add objects to them, and position those objects. You can style objects from built-in shape libraries, manually, or from style strings. Those objects can be shapes, containers, or edges to connect them. Finally you can save your diagrams where they can be opened with the Draw.io app.

See the full documentation for these functions in [Basic Diagrams - Usage](usage/basic_usage.md).

# Extended Functionality

Drawpyo extends the basic functionality of the Draw.io app with custom diagram types. These custom diagrams have automated styling and layouting to make common or complex diagrams easier to generate.

## TreeDiagram

This diagram makes creating directed tree graphs easy. Define trees, nodes, and the apply an auto layout.

[Documentation](diagram_types/tree_diagrams.md)