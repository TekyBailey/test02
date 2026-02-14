# Test02
Date Created: 14 Feb 2026

### Purpose Test02
Test a GitHub pages deployment method from the main or gh-pages branch using GitHub Actions. A website will be created using HTML, CSS, Markdown and 11ty SSG.



## Test01a

### Purpose
The Test01 repository will be used to test a GitHub pages deployment from the "docs" folder of the main branch using the default jekyll GitHub Actions. A website will be created using just HTML and CSS.

### Observations
1. Even though the deployment is from the docs folder of the main branch a build/deploy action is iniated anytime a file is changed in the main branch not just the docs folder. The default build/deploy action does NOT update the docs folder so any changes will not deploy to the Github artifacts and the website will not be updated. <br>
**Actions:** For this to be useful a custom actions script must be created and used to transfer the required contents of main into the docs folder. <br>
**Actions:** Revert the settings to the Test01 configuration.


## Test 01

### Purpose
The Test01 repository will be used to test a GitHub pages deployment only from the main branch using the default jekyll GitHub Actions. A website will be created using just HTML and CSS.

### Observations
1. How you name your repository affects how the url is generated. For example I named this repository "Test01" and the url generated was "https://tekybailey.github.io/Test01/". I have 2 observations about this:
- You have to type the link exactly as displayed from the pages tab. <br>
The link www.tekybailey.github.io/Test01/ is NOT allowed. 
- Capitalization is enforced (at least in the chrome browser) in the url. <br>
So the link https://tekybailey.github.io/test01/ does not work. <br><br>
**Action:** Name all repositories in lower case since most people will type the url in lower case anyway and may think the link is broken if it contains a capitalized letter and they type it as a lowercase.
