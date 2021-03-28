---
created: 2021-03-28
keywords:
  - guide
  - automation
  - zettlr
  - git
---
# Automating my Zettelbox and Wiki
20210328183346

extending the basics of [[20210328181358]] automating git push/pull with batch

```bash
echo "the cwd is %CD%"

echo "pulling changes"
cd "zettelkasten"
git pull
git checkout master

cd "..\wiki"
git pull
git checkout main


echo "starting zettlr"
start "" /wait "C:\Program Files\Zettlr\Zettlr.exe"


::push in \wiki
push "zettlr close"
cd "..\zettelkasten"
::push in \zettelkasten
push "zettlr close"


exit
```

## Sources
