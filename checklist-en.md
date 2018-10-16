## 1. Allowed markdown syntaxes on Devchecklists:
  * [ ] Github removes empty spaces when it compiles a markdown file. For a correct visualization of some pieces of code, please access the [raw version](https://raw.githubusercontent.com/vintasoftware/devchecklists-template/master/checklist-us.md) of this file.
  * [ ] `##` for titles.
  * [ ] `* [ ]` syntax to create a parent checklist.
  * [ ] `    * [ ]` syntax to create a second-level checklist.
  * [ ] `    * E.g.` syntax to create a second-level sample.
  * [ ] `      * E.g.` syntax to create a third-level sample.
  * [ ] Syntax for a simples piece of code `This is code`.
  * [ ] Syntax for code blocks:
    ```
    # Code Block:
	This is a 
	piece of code 
	in a block
    ```

## 2. Syntaxes to avoid:
  * [ ] `      * [ ]` third-level checklists.
  * [ ] `![Alt](/image.png "Image")` images.
  * [ ] Header syntaxes besides `## Header 2`:
      ```
      # Header 1
      ### Header 3
      #### Header 4
      ##### Header 5
      ###### Header 6 
      ```
