This example illustrates how to use object properies to make
existential restrictions.

In OWL, it helps to think in terms of the set of entities represented
by each class. To say: "every finger is part of a hand" we say:

  finger SubClassOf part_of some hand

The anonymous class expression "part_of some hand" represents the set
of all instances that have a part_of relationship to a hand. Every
member of the set of all fingers is a member of the set of all things
that are part of a hand.

Instructions:


# Open er-sec-complex.owl
# Navigate to the class "protein complex" using the search box
# Add a class 'endoplasmic reticulum Sec complex' as a subclass of "protein complex"
# Say that every ER-Sec-complex is part of a rough endoplasmic reticulum membrane
# Say that a ER-Sec-Complex has a Sec61 translocon complex as part
# Save your ontology, we may come back to it later

Hints (not particularly helpful):

If you like you can look up AmiGO/QuickGO or consult the current GO in
Obo-Edit to guide you. See also the HINTS.obo file.

Navigating over the resulting ontology:

# navigate to "rough ER membrane"
# Find the parts of the rough ER membrane. (Hint: What does the Existential tree show you?  Explore Window->views.)
## Let an instructor know you're at this point, they will review the two solutions to this question.
