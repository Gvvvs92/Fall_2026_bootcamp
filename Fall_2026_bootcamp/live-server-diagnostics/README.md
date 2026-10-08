You will need to use these files to create the necessary folder structure and files that satisfy the lab requirements for lab 5 (09/25/2026).

KEEP IN MIND:
- These instructions are high-level and vague by design. if you are unsure of what is meant by any step, you must watch the class video replay to see how to implement these steps

- The class video will not be a 1-1 with the instructions. During the lab, several students may experience issues that warrant troubleshooting or cause adhoc deviations from the below steps. 

	*You will need to exercise critical thinking and discernment to assess what steps correlate to certain portions of the video*

- the file names of the files given to students as reference during class will not match the file names given in this folder. The ordering in which students generate the files may also be slightly different.
	*Again, exercise discernment on context cues in the video vs. what is given in these instructions to generate the final result described below.*
------------------------------------------------------------------------------------


Ensure that you create a new branch on your repo so that you can PR and merge upon lab completion.

Your ending structure and files should be as such:

live-server-diagnostics/
├── diagnostics/
│   ├── python/
│   └── shell/
├── logs/
└── reports/

live-server-diagnostics should sit within your fall_2026_bootcamp repo


1. Use the commands in 00-starter-cmd.txt to create the necessary folder structure
	(MAKE SURE YOU ARE IN YOUR <fall_2026_bootcamp repo>, which should have been created in lab 2)

2. You will use the following workflow to create each of the files you need:

	touch <filepath\filename.ext>
	
	vi <filepath\filename.ext>
		*Use proper vi keys to paste in text from the corresponding text file*
		*remember to properly save and exit the file with wq!*
	
	cat <filepath\filename.ext>

3. Repeat steps 2 for files 01-07, creating and populating the appropriate files 

4. Execute chmod +x for all .sh files created

5. Execute you orchestration script by running ./main.sh from you CLI
	*ensure you are at the correct directory to actually execute this file*

6. If successful, you should have new text files generated in the reports/folder

7. Run you git workflow to stage, commit, and push the changes to you branch

8. Create a PR and merge your new branch back into main