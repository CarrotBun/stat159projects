

#sections:
#	mkdir ~/stat159/stat159projects/project01/paper/sections

#make md files: 
#	touch ~/stat159/stat159projects/project01/paper/sections/{00-abstract,01-introduction,02-discussion,03-conclusions}.md

paper.md: paper/sections/00-abstract.md paper/sections/01-introduction.md paper/sections/02-discussion.md paper/sections/03-conclusions.md
	cd paper/sections; cat *.md > paper.md
	cd paper/sections; mv paper.md ../

paper.html: paper/paper.md
	cd paper; pandoc -s paper.md -o paper.html
paper.pdf: paper/paper.md
	cd paper; pandoc -s paper.md -o paper.pdf




  