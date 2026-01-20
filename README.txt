# Lori Berebrain
this repository hosts my github pages website.

## pages
- home: index.html
- publications: publications.html
- teaching: teaching.html
- fieldwork & photos: fieldwork.html
- cv: cv.html (downloads cv.pdf)

## adding images
place images in `images/` and reference them like:
`<img src="images/myphoto.jpg" alt="">`

## local preview (mac)
from the repo folder:
python3 -m http.server 8000
then open http://localhost:8000

## deploy
github repo → settings → pages → deploy from branch → main → /(root)
