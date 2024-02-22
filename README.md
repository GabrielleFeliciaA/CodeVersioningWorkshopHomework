# CodeVersioningWorkshopHomework

**Comprehensive summary of the topics**
# Branching Summary
Branching in Git is a method for diverging from the main line of development to work on new features, bug fixes or any experiments without affecting the main codebase. Branches in git are simply pointers to a specific commit.

Advantages of branching:
1. Branches in Git are lightweight and inexpensive to create. Creating branches doesn't consume/need much storage or memory.
2. It's easy to logically divide up work into separate branches which allows developers to work on different features or fixes independently without interfering with each other's changes.

How to branching?
- Create branch:
    ` $ git branch < branch > `
- Switch to branch:
    ` $ git checkout < branch > `
- List all branch:
    ` $ git branch
    
Combine command:
` $ git checkout -b < branch > `
The command above is used to create a new branch and switch to it in one step.

Delete branch:
`$ git branch -d < branch >`

# Merging Summary
Merging in Git is the process of combining or integrating the changes made in one branch to another branch. This allow us to branch off, develop a new feature and then combine it back in.

Merging Analogy: 
Merging in git creates a special commit that has 2 unique parents. This means "I want to include all the work from this parent over here and this one over here, and the set of all their parents"

How to do merging:
` $ git checkout main `
` $ git merge < branch name > `

The Advantage of Merging:
Merging in Git merges two branches together while keeping both branches' histories intact, including the timing and context of all changes. 

Disadvantage of Merging:
Sometimes histories preserved become to a convoluted web of stories, making the project history more difficult to follow.

**Challenges faced during the assignment and how I overcame it**

The challenge I faced when working on this assignment is during pull requests and code reviews because this material haven't been taught in the training class yet. However I overcame this challenge by figuring it out on my own through Google and Youtube, and by discussing with my colleague. 
