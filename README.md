# testing
a test repository to understand the working of the github

This is the first line written from the main

This line is written after the creation of feature branch.

It is obvious that you can create a pull request to merge the changes in the feature branch  to the main branch.

what if a change is made in the main branch , can it be automatically merged in to the feature branch
or a new pull request should be raised?

Answer is that the pull request must be raised rom the main branch and once it is raised you must open the pull requests and merge those 
changes in to the feature branch.however you would see the line in your feature branch saying that it is behind the main branch by 
specific number of commits, and that is how you will come to know that there have been some changes in the main branch(the branch based on which
you have ceated the feature branch).

suppose that you have two feature branches and you updated a file in feature1 branch and you want to create a pull request from feature1 branch to feature2 branch will it work?

Yes , ofcourse it will 

Suppose that we have 20 branches in a repository , and one of the branches have done the changes,how does one knows if there are any changes in the repository ?

If a change is made in any of the branches you would see the highlighting sayiong that there are changes from this branch as shown .....

new line from main

new line from feature


test :

1. create two feature branches from main branch.
2. make the changes in fbranch 1 and also in fbranch 2.
3. push the changes to main from both the branches and write the comments below.



# process :
--> changes from fbranch1.

--> changes from fbranch2



# findings :

done the changes from fbranch1 and fbranch2.

created a pull request to main branch from both the branches.

when first opened a pull request from fbranch1 ,there were no conflicts and there were notifications while creating

a pull request saying that there has been changes in the 

feature branches to the main branches ,so compare them and pull the changes before raising the merge request.

there you will have an option to compare two branches and merge before raising the pull request.

--> when you try to merge the changes in with the main branch by opening the pull request, there were no conflicts.

meanwhile i have raised the pull request from fbranch2 and ofcourse got the same notifications like earlier

But when i opened the pul request to merge the changes there was a conflict which i had to manually choose which changes should be there in the main branch.


