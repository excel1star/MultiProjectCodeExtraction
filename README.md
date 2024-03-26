# MultiProjectCodeExtraction

This code project extracts Modules and Elements( SUBS, FUNCTIONS, and TYPES) from a collection of Excel Projects.
It generates a KDIFF-like matrix that identifies similar modules and elements from the various projects. And a Library of Elements from all the projects.
2. It Collects all modules and elements from each project into a separate folder.
	This folder can then be presented to KDIFF for analysis.
3. All the elements from the collection of projects are cataloged into a library folder.
	The individual elements are labeled with their name and an ad-hoc hash code this prevents elements with the same name but with variations in their code from colliding.
