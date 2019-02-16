# first-hole
Just Testing the ground water..
(1) Created repo - with this readme
(2) Created branch readme-edits to poke further into this hole
(3) Added some shiney new words to this readme ( Make and Commit Changes bit )

Next.. To add a commit massage to describe what I've done.. then poke around to find and click the commit thing..

 (4) Now changing again locally to add line for issue01 - But now added some words in GITHub editor :)
 
 
 Note - Merging a pull request created on GItHUB via the command line rather than [Merge pull request] as an example ..
 
 #### Merging via command line
If you do not want to use the merge button or an automatic merge cannot be performed, you can perform a manual merge on the command line.

HTTPS
Git
Patch
	
**Step 1:** From your project repository, bring in the changes and test.

 git fetch origin
git checkout -b stilldigging-patch-1 origin/stilldigging-patch-1
git merge master

**Step 2:** Merge the changes and update on GitHub.

 git checkout master
git merge --no-ff stilldigging-patch-1
git push origin master


