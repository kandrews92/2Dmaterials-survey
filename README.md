#termpaper

	
	Repository for PHY 7050 term paper.

	Current structure:


	two-dim-materials/:
  		articles/
			reviews/
			#contains survey articles that give a useful overview 
			of topic

			unread/
			#contains articles that have yet to be read and 
			placed into a specific category

		bibs/
			#contains bibtex file for the papers contained 
			in articles dir
	
		outline/
			#contains outline latex file for report

		report/
			#contains latex file and subsequent latex files needed 
			for compiling final report file (note: .tex files that 
			reference any bib file should reference the bibs/ dir)

		presentation/
			#talk.tex and supporting files for presentation and 
			talk 

		figs/
			#any figures that are to be used in susequent files or
			directories under the branch termpaper/
