   git commit -a -m 'pulando a stage'
   git rm LICENSE.md
   git rm --cached README.md 
   git mv ola.py hello.py
   git log
   git log -p -3
   git log -p -2
   git log --stat 
   git log --pretty=short 
   git log --pretty=oneline 
   git log --pretty=full
   git log --pretty=fuller 
   git log --pretty=format: "%h - %an, %ar : %s"
   git log --pretty=format:"%h - %an, %ar : %s"
   git log --pretty=format:"%h -> %s"
   git log --pretty=format:"%h -> %s: %ar"
   git log --pretty=format:"%H -> %s: %ar"
   git log --pretty=format:"%H -> %s" --graph 
