# lookthepart-android

**Roadmap for React Native:**
https://docs.google.com/document/d/1GlevsApSL9Sw_T6NIjGWikX2nK0ft7c2ooJt3YblhPY/edit?usp=sharing

**Backend APIs - Postman Collection:**
Please find postman collection file under main branch, named as "LookThePart.postman_collection.json"

BRANCHING STRATEGY:

**Master branch**

This is the main branch and repository with the most recent stable production code.
Direct merges into this branch should be restricted.


**Release branch**

Release branches facilitate the creation of a new production release. Once we have all of the tickets in the develop branch that should be in the next release, we should create a separate release branch with a proper version number (e.g., Release-1.0), so that the development team can continue working on next release items and freely merge them to the develop branch.


**Develop branch**

This branch will be used primarily to push ongoing development work to the Dev environment.
The Develop branch combines multiple feature branches into a single branch and deploys it.


**Feature Branches**

Developers create separate branches for each feature they work on.
Each feature branch is independent and can be developed and tested without affecting the main branch.


**Branch Naming - Best Practices**

![Branch Name - Best Practices](https://github.com/LookthePart/lookthepart-android/assets/112682844/0e313682-577c-47fe-8a4f-da4e9159bd04)


Please read this article to learn the best practices for Git Branching Strategy:
https://nvie.com/posts/a-successful-git-branching-model/
