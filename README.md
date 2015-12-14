# JT-ProjectOne
A very simple DNA analysis program in Python based on  Rosalind and Coursera Genomics Data Science projects

Project proposal:

Summary:
A simple DNA manipulation program accepting user input either from keyboard or as a file. Program does a limited number of functions and produces output as either direct command line output or as a document file.

I would like this project done in a week or less. I think it could be finished much faster, but this allows for everyone to work at times best suited to them and allows everyone to verify usability and acceptability overall.

Team:
Ideally one team member for each function below + one Github coordinator (this could be one of the function writers.

Special Requests: I am not experienced with Github, but I would like to learn how to manage a team project using this system. If one team member could be in charge of this organization, that would be ideal.

Elements:
1. Accepts input of DNA
2. Checks DNA file for bases (accept only A,T, G, C), provides an explanation of why file is rejected.
3. Finds ORFs (only in one direction at this point, but in all three frames)
4. Translate ORFs into AAs


Specific Functions:

User Input function- prompts user for DNA sequence either as raw input or as a file (FASTA format)
whether user input or file input, be sure to capture sequence and an identifier
example of FASTA file format from (https://www.genomatix.de/online_help/help/sequence_formats.html):
2. Sequence Checker - for either type of file, check entire sequence and report:
	a. Does file consist of only A,T,C,G? 
		1. If not, reject - inform user that file is rejected and provide reasoning
		2. If so, accept - inform user file is accepted
	b. Convert all characters in file to uppercase (run this no matter what, to ensure proper format.
	c. Provide feedback to user indicating length of file in bases (bp)

3. ORF finder - find ORFs in all three forward Frames.
	use standard start and stop codons to define limits of the ORF
	Build a dictionary of ORFs.noted as  starting base and ending base (i.e. 25, 46)

4. Translate ORFs
	build a second dictionary of starting locations and string of AAs (e.g. 25, ‘MHTYPLI’)



User Interface:

User interface should be clean and clear. All done in command line. If input is expected, be sure to prompt user for the kind of input they should provide.
Separate Input from Output in a clear way ( e.g. a number of newlines or string of symbols (e.g.  ‘**************’)


Input Format: As stated above


Output Format: As stated above
