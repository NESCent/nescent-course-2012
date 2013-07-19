This example illustrates adding classes and class annotations into an existing SubClass hierarchy.
* The example does not make use of reasoning / automated classification or class expressions.

Constructs illustrated:

 * SubClasses (adding them)
 * Annotations
 * DatabaseCrossReferences (=xref)

Instructions:

# Open chromosome-parts.owl

== Subclasses ==

# Add the term "replication fork" to the ontology under "chromosomal part".
  * Don't worry about the ID

Moving around classes: 
# Add the term "intracellular non-membrane-bounded organelle" as a SubClass of "Thing"
# Move it, by dragging and dropping, to place it as a Subclass of non-membrane organelle {MJY's interpretation}

== Annotations == 

* The goal is to replicate the existing information from GO on the "replication fork" class. 

# Click on this class you just created.  
  # Use the (+) next to Annotations to add an annotation.
  * You can find existing values in GO, or in the HINTS.obo file
  # Add the following (using the values that you found)
    # A text definition for the class
      # Click on the "replication fork" class, then click (+) by Annotations
      # Choose the "Constant" tab
      # Click (select) "definition" on the left
      # Enter the defintion in the "Value" window.  You can leave Type and Lang blank.
      # Click OK. THe annotation should appear in the Annotations window.
    # 2 def dbxrefs to the text definition
      # Click the (@) icon beside the definition annotation
      # Click the (+) beside annotions
      # Select "database_cross_reference" in the left pane
      # Enter a value
      # Repeat for the other cross reference by clicking (+) in the "Annotations for AnnotationsAssertion window" that follows
    # A related synonym
      # Add an annotation to "replication fork" with the (+)
      # Choose "has_related_synonym" and enter the value
    # An xref to the class itself

Synonym properties:

# Add the SubClass "site of double-strand break" to the ontology under "chromosomal part"
 # Add a synonym dbxref. E.g. synonym: "site of DSB" EXACT [PMID:21035408]
    # Click (+) to add a synonym
    # Select "has_exact_synonym"
    # In the Constant tab, in the value field, add "site of DSB"
    # Annotate this anntation with "synonym_type_property"
    # In the value field add 'EXACT [PMID:21035408]", click to continue.  Notice that the synonym anntotion (@) is no yellow indicating it has an annotion.
    * What is the difference between an exact and norrow synonym?
    * What is the purpose of the word "EXACT"?
    * What are the logical consequences of the "EXACT" specification?
 # (bonus) Replicate the remaining annotations found in OBO for this class  

