# GitProject
Git Hub Project of Phase 1 - FSD course

Build a branching model as depicted in this figure
1.	Start with the production branch and then create a HotFix branch and Integration branch
2.	Subsequently have Feature 1 and 2 branches that integrate as shown in figure
3.	Ultimately integrate all features into HotFix branch and then to Production branch

Solution

Step 1:  In master branch (Production branch) create commit “1”
Step 2: Create HotFix and Integration branches (git branch) from the master branch
Step 3: Create commit “2” into Production branch which is the master branch
Step 4: Make commit “1” in HotFix branch
Step 5: Create two feature branches from the Integration branch, namely Feature branch 1 and Feature branch 2
Step 6: Create three commits in Feature branch 2 and merge into Integration branch creating commit “2”
Step 7: Delete Feature branch 2
Step 8: Have three commits in Feature branch 1 and rebase it from commit “2” in Integration branch
Step 9: Merge Integration branch commit “2” into HotFix branch and into Production (master) branch commit “3”
Step 10: Make another commit in Feature branch 1 and merge into Integration branch creating commit “3” and merge into HotFix (“3”) and Production (“4”)
Step 11: Delete Feature branch 1
Step 12: Create a commit on HotFix branch (“4”) and merge that into both Integration (“4”) and Production branches (“5”)

