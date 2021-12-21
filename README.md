# Student Lecture Notes

## For visitors
University provided lecture notes useless? Had to skip a lecture? Want a different perspective on the content? Then this project may help you. We do not have a website with easy to view notes yet, but this will come very soon. 

## For contributors

### Acceptable formats
We currently only accept LaTeX, MarkDown, and HTML* as file formats. I am open to other formats, provided they can be automatically and sanely converted to HTML. If you have good notes in an unacceptable format, you may put them in staging/

*any \<script\> tags or custom CSS will be removed by the script that converts all notes in this repository to website content. Any external content will not be updated daily, but rather will be pulled to the website server by the script once. For the stated reasons, the use of HTML directly is discouraged. 

### Directory structure
Structure your notes directory in the format notes/\[Institution\]/\[Class ID\]/\[Lectures|Discussions|ExamPrep\]/\[Academic Term\]/\[Entry Label\]. The first person to commit from any given institution will set the precedent for the institution's directory name. For example:

notes/UIUC/MATH-231/Lectures/fa2021/Week1-Lecture1
notes/UIUC/MATH-231/Lectures/fa2021/Week3-Discussion2
notes/UIUC/MATH-231/Lectures/fa2021/Midterm2-Prep

### Metadata schema
It is a good idea to provide metadata. The schema for metadata has not been decided on yet. It will likely consist of a set of TOML files under a specific structure. 

### Contributor guidelines
Please use common sense with regards to how you treat other contributors and the project. If there is a personal conflict, please try to leave it out of academic discussions. If there is a dispute in academic content then it will be resolved through discussion on the Pull Request in question. If academic content differs between academic terms, it may remain separate if resolution is impossible. However, a conflict between notes produced within or close to the same term will have to be resolved. Final discretion is up to the maintainers.
