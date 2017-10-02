# polidoc
Development platform for polidoc.net

# Intro
- Contents of polidoc.net are now tracked using country- and region-specific files, which replace the "Bestandsliste" 
- Manifesto- and party-level data stored in .csv files (can be edited in Excel and used by R) to track manifesto and party coverage
- These contain country names and acronyms, cmp codes, election years covered, manifesto titles, original and english party names as well as party acronyms 

# Workflow
- Files are assigned, edited, committed, controlled, and integrated via GitHub
- Use "Issues" to assign files and tasks  
- Use "Pull requests" for open questions/review  

# Codebook
- polidoc_manifestos.r creates tables and figures from the data to be used in the codebook 
- polidoc_codebook.tex creates the codebook from these files and only needs to be re-run for an update 

# Wishlist
- Scrape polidoc.net to update files or create polidoc.net from files
