It Fix Guide - 123 guides
index.html             = the web app (single file, open in a browser)
images/svg, images/png = illustrations for guides 29-122 (gNNN = guide id; PNG 800x480)
                         guides 0-28 already have photos inside index.html
docs/image-brief.csv   = image work order for hand-made images
source/r1..r4, ex      = content drafts per round
source/gen/            = illustration generator (node build.js; edit scenes.js to change which icons a guide uses)
source/merge2.py       = merge drafts: python3 merge2.py r4/all.txt index.html 99
source/t.js            = Playwright test
