# Résumé versioning automation and document creation
Convert your résumé automatically into PDF and docx formats on save. Keep a record of the changes you've made to your résumé for each employer you submit it to.
The résumé is in Markdown format, a simple text format document. Here's a [cheatsheet](https://github.com/adam-p/markdown-here/wiki/markdown-cheatsheet)

**Benefits:** 
- Only one file to maintain and update

- Versions are automatically saved and accessible

- ATS machine-readable files

## How to use
- Click the `Use this template` button, and create a new repository, follow the Create New Repository prompts

- Set the Action Secret. You only need to do this once. Create a Repository Secret in Settings > Secrets and variables > Actions. Make sure to set the permissions to Read and Write, click save.

- Update [name.txt](name.txt) with your name with an underscore between first, last: `First_Last`. This will be the name of the PDF and docx files, followed by `_resume`.

- Update [resume.md](resume.md) with your desired content.

- Commit the changes either to a new branch or main, the corresponding PDF and docx files will be updated in the output directory.

- Download the files as needed 
