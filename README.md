#two-dim-materials


	Author: Kraig J. Andrews
	
	Date Created: 26/02/2015
	
	File: README.md

	Purpose: 
		-Give overview of directory structure
		-Describe contents of each subdirectory 
		-Reference any notes or structural issues needed for 
			referencing *.bib, *.png, etc... files in a 
			*.tex file
	
	Repository for condensed matter literature survey on two dimensional
	material beyond graphene and their applications

	Current tree:

	two-dim-materials/
		articles/reviews/..
			unread/..
		bibs/..
		macros/..
		outline/..
		presentation/..
		report/..
		scripts/..
		README.md
		clean



	two-dim-materials/:
		
		"clean" (shell script): 
			for cleaning out dirs by removing
			unneeded structural files before committing and then
			pushing them to git repo. 

  		articles/:

			reviews/:
				contains survey articles that give a 
				useful overview 
				of topic

			unread/:
				contains articles that have yet to be 
				read and placed into a specific category

			graphene:/
				specifically articles relating to the 
				development and study of graphene

		bibs/:
			contains bibtex file for the papers contained 
			in articles dir
	
		outline/:
			contains outline latex file for report

		report/:
			contains latex file and subsequent latex files 
			needed for compiling final report file 
			(note: .tex files that reference any bib file 
			should reference the bibs/ dir)

		presentation/:
			talk.tex and supporting files for presentation 
			and talk 

		figs/:
			any figures that are to be used in susequent 
			files or directories under the main branch

		macros/:
			"units.tex":
				macros for commonly used units. 
				this should be referenced directly
				in each *.tex file it is used in

		scripts/:
			"mk":
				compiles latex in a given dir
				must be placed in desired dir to compile
			"clean-template":
				rm's any files that aren't necessary
				for preservation, i.e. *.aux, *.toc, etc.
				before pushing to repo for space
				conservation. Just a template file. 
				For reference, if needed.
