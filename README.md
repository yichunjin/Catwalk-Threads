# Catwalk Threads
React web application designed for users to enhance the online shopping experience.

## Main feature

### Product Overview
- Product Information
- Style Selector
- Add to Cart
- Image Gallery with zoom in
- Dark mode and light mode

### Ratings & Reviews
- Write new review
- Reviews List
- Sorting 
- Rating Breakdown
- Product Breakdown


### Questions & Answers
- View questions
- Search for a question
- Asking a question
- Answering a question


### Related Items & Outfit Creation
- Related Product Cards
- List Behavior
- Related Products List
- Your Outfit List

## Technologies Used
- [React](https://reactjs.org/)
- [Node](https://nodejs.org/en/)
- [Express](https://expressjs.com/)
- [CSS](https://github.com/css-modules/css-modules)
- [AWS EC2](https://aws.amazon.com/?nc2=h_lg)

## How to Run
Navigate to the root directory of FEC, then install the required packages by running `npm install` in your terminal. To begin, first compile the by running `npm run react:dev`, then start the server by running `npm start:dev`. Lastly, navigate to `http://localhost:1128` in your browser.

## Opening a PR
When you're ready to merge your fork with FEC:Master, open a PR and merge.

## To Resolve a Conflict

### Manual Option
Pull from your upstream or master, depending on where the conflict is happening. Next, checkout your working branch and run `git merge upstream master` to merge the master branch with your master branch. Then, resolve the merge conflicts on your local machine. Finally, push your changes and open a new PR.

### Rebasing Option
Fetch all branches of remote upstream with `git fetch upstream`. Next, rewrite your master with upstream’s master using `git rebase upstream/master`. Then, push your updates to master. You may need to force the push with “--force”. `git push origin master --force`. Lastly, open up a new PR.
