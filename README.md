# BSCIT-Notes

Re-created version of College Notes website based on Jekyll.

### Structure

```
--index.html (Front page)
--dm.html (Disecrete Mathematics front page)
--de.html (Digital Electronics front page)
--ip.html (Imperative Programming front page)
--os.html (Operating System front page)
--bc.html (Business Communication front page)
--upload.html (Add notes front page)
--css
  -custom.css (Original CSS)
  -skeleton.css (Framewor)
-- _layout (Website theme )
  -dm
  -de
  -ip
  -os
  -bc
-- _posts (All Indexed Files Directory)
-- _config.yml (Jekyll configuration file)
```

  - Files above 100mb are stored on https://archive.org/
  - Build with HTML,CSS, JavaScript and Jekyll

### How to index ?
>> Inside _posts folder.
All files are named in a specific way "YEAR-MOTNH-DATE-CATEGORY-post-NUMBER"
    e.g: 2017-08-15-bc-post-01
    
Categories list 
  - Business Communication - bc
  - Operating System - os
  - Digital Electronics - de
  - Disecerte Mathematics - dm
  - Imperative Programming - ip
  
  1) Copy existing post (category of yourchoice) and Paste in the same directory.
2) You will be promoted for "Either Rename or Overwrite" choose Rename and change the 'post number' such that it should be an increament to the previous/last existing post of that category.
3) Open the newly copied file in a text-editor.
```
---
layout: default
title: Persuasive strategies in business communication
meta: 747 KB
source: https://github.com/purplecandy/college/raw/master/uploads/bc/Communication%20Skills.pptx
category: bc
icon: <img class="sicon"src="http://bit.do/img-ppt">
---
```
4) layout should be set to default
5) Here title: Appeared Post Title, meta = file size, source = download link; category: post category; icon = depending on the file extion change the last word of the url into "word" or "ppt" or "pdf" to change the icon.
6) Save if everything is done properly you will see a new post under the category
