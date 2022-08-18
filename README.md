## CMPG-323-Overview - 35359099
#
### Repositories to be created:

The following repositories will be created in order to facilitate work on various projects throughout the semester.

| # | Repostiory Name | Purpose |
| - | - | - |
| 1. | CMPG 323 Overview - 35359099 | Agile & Scrum | 
| 2. | CMPG 323 Project 2 - 35359099 | API Development |
| 3. | CMPG 323 Porject 3 - 35359099 | Standards & Patterns |
| 4. | CMPG 323 Project 4 - 35359099 | Testing & RPA |
| 5. | CMPG 323 Project 5 - 35359099 | Reporting & Monitoring |
#
### Project & repository context diagram:
![Context Diagram](./context_diagram.jpeg)
### Branching strategy:
All repositories will have a **Master** and **Development** branch.

Regular commits will be pushed to the development branch before being reviewed and pulled into the **Master** branch. The Master branches for each repository will contain the final completed version of the project.
#
### Usage of .gitignore:
The .gitignore files will be used to ignore all non-essential/senstitive files.

- Config Files
- Database Files
- External Libraries (Should only be included in compiled release version)
- Credential Files
- Files/Folders generated during runtime
- Compiler/IDE specific config files
- Crash/Log Files
#
### Storage of credentials and sensitive information:
During development all credentials will be stored within a local JSON config file. The config file path will be added to the .gitignore file so that it is not pushed to the public repository. 

During production all important credentials must be stored as environment variables on the server/service which hosts the project.
#

Reference list:
1. Gitignore Explained, Author: freecodecamp.org, 
Date Accessed: 2022/08/10 URL: https://www.freecodecamp.org/news/gitignore-what-is-it-and-how-to-add-to-repo/ 
2. Storing credentials the right way, Author: Abhishek Pathak, Date Accessed: 2022/08/10 URL: https://medium.com/developer-secrets/storing-credentials-the-right-way-78074ae21727