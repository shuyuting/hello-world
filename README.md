# hello-world
just another repository

this show how to use with lunix


now i just learn how to use it


command to remember for GitHub

1 git clone [limk]

bash-4.2$ git clone https://github.com/ahussaini821/Bioinformatics-project
Cloning into 'Bioinformatics-project'...
Username for 'https://github.com': shuyuting
Password for 'https://shuyuting@github.com': 
remote: Enumerating objects: 17, done.
remote: Counting objects: 100% (17/17), done.
remote: Compressing objects: 100% (12/12), done.
remote: Total 17 (delta 3), reused 8 (delta 0), pack-reused 0
Unpacking objects: 100% (17/17), done.
bash-4.2$ git pull
fatal: Not a git repository (or any parent up to mount point /homes/ys315)
Stopping at filesystem boundary (GIT_DISCOVERY_ACROSS_FILESYSTEM not set).
bash-4.2$ ls
019-10-03-population_genetics	      igv
1svk_Gprotein_alignment_wrk2.fa       learning1_exercises
2019-10-01-assembly		      learning_exercises
2019-10-01-gene_prediction	      lianxi10.pdf
2019-10-01-read_cleaning	      lianxi2.pdf
2019-10-02-genotyping		      lianxi3.pdf
2019-10-02-mapping		      lianxi4.pdf
50001_MH8688_20141231_A.fastq	      lianxi5.pdf
50001_MH8688_20141231_A.fastq.save    lianxi6.pdf
50001_MH8688_20141231_A.fastq.save.1  lianxi9.pdf
A_California_09.fa		      ls_orchid.fasta
A_Perth_10.fa			      mozilla.pdf
Bioinformatics-project		      Music
calp.fa				      mymax.py
calp.fa.amb			      mymax.py.save
calp.fa.ann			      mymax.py.save.1
calp.fa.bwt			      ooop.pdf
calp.fa.pac			      P04637.fas
calp.fa.sa			      Pictures
CHICK.fasta			      protein bioinformatics
coding_for_scientist		      protein_p53.save
colours.txt			      protein_p53.save.1
Desktop				      Public
di1zhou2.pdf			      R
di1zhou3.pdf			      runner.
di1zhou4.pdf			      runner.sh
di1zhou5shang.pdf		      Scratch
di1zhou5xia.pdf			      shoppinglist
di2gezhou1.pdf			      shoppinglist1
di2zhouzhou2i.pdf		      shoppinglist.tar
di2zhouzhou2lianxiti.pdf	      Templates
di2zhouzhou3ishang.pdf		      testdir
di2zhouzhou3lianxitishang.pdf	      Untitled1.ipynb
di2zhouzhou3lianxitixia.pdf	      Untitled2.ipynb
di2zhouzhou3shang.pdf		      Untitled3.ipynb
di2zhouzhou3xia.pdf		      Untitled4.ipynb
Documents			      Untitled5.ipynb
Downloads			      Untitled.ipynb
drinks.txt			      UP000000539_9031.fasta.
fastatio.py			      UP000000539_9031.fasta.gz
fruit.txt			      UP000000539_9031.fasta.tar.gz
HA_H1N1				      venv
hello.py			      Videos
hello.py.save			      WHATIDID.txt
hg38.fa.gz			      zhenzhenglianxi3.pdf
hierarchy

2 git pull#make a branch

bash-4.2$ cd Bioinformatics-project/
bash-4.2$ ls
Codetest.py  README.md	test2.txt  test.txt
bash-4.2$ git pull
Username for 'https://github.com': shuyuting
Password for 'https://shuyuting@github.com': 
From https://github.com/ahussaini821/Bioinformatics-project
 * [new branch]      Pedro      -> origin/Pedro
Already up-to-date.
#
#you must creat a branch yuting at first in Git website
#
bash-4.2$ git checkout yuting
Branch yuting set up to track remote branch yuting from origin.
Switched to a new branch 'yuting'
bash-4.2$ git branch
  master
* yuting

3 git add test.R

bash-4.2$ vim test3.txt
bash-4.2$ git add test3.txt 

4 git commit-m"added graph"

bash-4.2$ git commit -m "Another commit"
[yuting 27aa382] Another commit
 Committer: Yuting Shu <ys315@ioc027.student.eecs.qmul.ac.uk>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly:

    git config --global user.name "Your Name"
    git config --global user.email you@example.com

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 1 insertion(+)
 create mode 100644 test3.txt
 
 5 git push
 
bash-4.2$ git push
warning: push.default is unset; its implicit value is changing in
Git 2.0 from 'matching' to 'simple'. To squelch this message
and maintain the current behavior after the default changes, use:

  git config --global push.default matching

To squelch this message and adopt the new behavior now, use:

  git config --global push.default simple

See 'git help config' and search for 'push.default' for further information.
(the 'simple' mode was introduced in Git 1.7.11. Use the similar mode
'current' instead of 'simple' if you sometimes use older versions of Git)

Username for 'https://github.com': shuyuting
Password for 'https://shuyuting@github.com': 
Counting objects: 4, done.
Delta compression using up to 6 threads.
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 293 bytes | 0 bytes/s, done.
Total 3 (delta 1), reused 0 (delta 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/ahussaini821/Bioinformatics-project
   2358f22..27aa382  yuting -> yuting


now have alreald submit your file
