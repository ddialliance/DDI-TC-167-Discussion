# Use of "default values" in DDI (cross-version) 
related issue: TC-167 https://ddi-alliance.atlassian.net/browse/TC-167

# GOAL:
The goal is to have consistent rules for the use or non-use of assigning default values (for example: default value for a decimal indicator in a data set or record type with the ability to overide at a specific value). These rules should be used to inform individual products in their use of defaults. While exception to a general rule should not be precluded the product should specify, justify, and document any exception.

# BACKGROUND:
Early in DDI Lifecycle development there were a number of requests for providing default values to save repetative entry by individuals creating XML instances. At that time the majority were hand crafted but this no longer seems to be the case. In addition, both Codebook and Lifecycle were highly nested so that it was clear what set of items the default value applied to. As we move to greater serialization and reuse of content, this may no longer be the case. This is particulary true in cases where metadata content is managed in a data base and the XML instance is generated from the data base content. In addition, there were later complaints that use of defaults (particularly inconsistent use of defaults) caused problems for implementation. 

# SPECIFIC ISSUES:
What are the advantages/disadvantages for content entry and for implementers.
* Raised in context of W3C and its use for, say, a comma delimited file (default values for delimiters, decimal separators, use of blank or "." for missing value, use of " for text, etc.).

Are there specific scenarios where use of defaults is appropriate? For example using a default at the RecordType level, file level, or item level.

How do common software packages consume default values? do they consume them at all?

# CONTRIBUTING TO THE DISCUSSION

To contribute to the discussion please file an issue at https://github.com/ddialliance/DDI-TC-167-Discussion/issues
