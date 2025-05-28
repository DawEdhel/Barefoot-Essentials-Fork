**Quickly adapt the script source's full internal changelog to Github's markdown style, using Notepad++ Find&Replace with regex search mode:**

* **replace a change's starting block:**  
Find: `[\t ]{0,}{\s{0,}"version": "(.{1,})",\s{0,}"date": "(.{1,})",\s{0,}"changes": \[`  
Replace with: `## \1 \(\2\)`

* **replace a change's ending block:**  
Find: `[\t ]{0,}\]\s{0,}}[,]{0,}`  
Replace with: `<empty space/nothing>`

* **trim change's individual lines and convert to list items:**  
Find: `[\t ]{0,}"(.{1,})",{0,}`  
Replace with: `* \1`

* **convert custom tags across changes' individual lines:**  
Find: `<small>(.{1,})</small>`  
Replace with: `<sub>\1</sub>`
