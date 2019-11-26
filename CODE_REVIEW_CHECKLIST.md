# Code Review Checklist

### README

* [ ] Readme includes instructions for running the project locally

### HTML

* [ ] Consistent Indentation
* [ ] Includes meta viewport tag for mobile devices  
  * `<meta name="viewport" content="width=device-width, initial-scale=1.0">`
* [ ] CSS Links and Font Links are in the head of the document
* [ ] JavaScript files are linked at the bottom of the page OR at the top with an onload function OR at the top with a defer attribute
* [ ] Uses semantic tags where available
  * header, time, main, nav, article, section etc.
  * See this article for more: https://html.com/semantic-markup/
* [ ] Title / Header links back to home page
* [ ] No extra elements. Only includes the necessary elements to make things work.

### JavaScript

* [ ] Consistent semicolon usage. Either do or do not. There is no inbetween.
* [ ] Consistent quote usage. Either `'` or `"`, don't mix.
* [ ] Consistent indentation.
* [ ] Reasonable max line length. Wrap / reformat code when it gets too long.
* [ ] Variable / Function names are clear and concise.
  * [ ] No abbreviations.
* [ ] Variable / Function naming convention is consistent. 
  * camelCase or PascalCase or snake_case
* [ ] Strings used more than once are in a variable.
  * API_URL etc.
* [ ] Functions are as few lines as possible. Code reads like a sentence.
* [ ] Function names dictate intent.
* [ ] Nested loops avoided where possible.
* [ ] Functions take in a reasonable number of parameters. Ideally 3 or less params. Otherwise, use an options object.
* [ ] No extra variables.

### CSS

* [ ] Consistent indentation
* [ ] Consistent naming convention
  * [ ] Uses app specific prefix where necessary
* [ ] No duplicate styles. Re-use where applicable.