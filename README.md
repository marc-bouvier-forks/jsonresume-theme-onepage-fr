# jsonresume-theme-onepage-fr

Un thème compact de JSON Resume, optimisé pour l'impression. 
Fork de [ainsleyc/jsonresume-theme-onepage](https://github.com/ainsleyc/jsonresume-theme-onepage)

Tries to fit as much information as possible onto a single page without making sections look cluttered.

## Example

http://themes.jsonresume.org/theme/onepage

## Running

```
sudo npm install -g resume-cli
git clone https://github.com/marc-bouvier-forks/jsonresume-theme-onepage-fr.git
cd jsonresume-theme-onepage-fr
resume serve
```
You can print directly from the served html.

## Options

For the "experience" and "skills" sections, you can optionally replace the "highlights" list with a "details" list with this format:

```
"details": [
  { "text": "Javascript", "comment": "expert" },
  { "text": "Coffeescript", "comment": "expert" },
  { "text": "Ruby", "comment": "competent" },
  { "text": "Java", "comment": "novice" }
]
```

See included resume.json for more details.

