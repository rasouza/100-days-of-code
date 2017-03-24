# 100 Days Of Code - Log

### Day 1: March 6th, 2017

**Today's Progress**: Started prototyping the app's layout.

**Thoughts:** Getting along with the template wasn't big deal since it already came developed under Angular. Still need to match the template's colors with my personal logo

**Link to work:** [Programming Diary](https://github.com/rasouza/diary)

### Day 2: March 7th, 2017

**Today's Progress**: Tried to add Material Datepicker lib

**Thoughts:** I struggled with including some 3rd parties' lib such as Material Design 2 (Datepicker). Maybe tomorrow I'll fix it or drop it

**Link to work:** [Programming Diary](https://github.com/rasouza/diary)

### Day 3: March 9th, 2017

**Today's Progress**: Fixed MD2 Datepicker

**Thoughts:** After some research, I found out it was as easy as including Angular's `FormsModule` to my module. Also I customized the datepicker to show only the button and open it through it.

**Link to work:** [Programming Diary](https://github.com/rasouza/diary)

### Day 4: March 13th, 2017

**Today's Progress**: Added services to communicate with the API

**Thoughts:** I thought that would be much harder to create a form-submit feature, but Angular really makes it easy

**Link to work:** [Programming Diary](https://github.com/rasouza/diary)

### Day 5: March 14th, 2017

**Today's Progress**: Rendered the timeline based on a service

**Thoughts:** I'm mocking the stories since I don't have the API up and running yet. Maybe tomorrow will have my hands on it. However, mocking data is usefull to check if your Angular code is right. Still need to implement automated tests

**Link to work:** [Programming Diary](https://github.com/rasouza/diary)

### Day 6: March 15th, 2017

**Today's Progress**: Changed theme's color and listed all my Github repos

**Thoughts:** Today I created a service, changed template's theme and included a 3rd party library all on my own. Previously, It took me a whole week and several hours of watching tutorials to accomplish it all. Tomorrow I'll start creating the backend API.

**Link to work:** [Programming Diary](https://github.com/rasouza/diary)

### Day 7: March 16th, 2017

**Today's Progress**: Created API and implemented OAuth2

**Thoughts:** I started the API since my Angular app is lacking backend functionality, implemented OAuth2 for GitHub on it but I have no idea on how to make it work in Angular

**Link to work:** [Programming Diary API](https://github.com/rasouza/diary-api-php)

### Day 8: March 17th, 2017

**Today's Progress**: Surveyed better ways to develop under CI approach

**Thoughts:** Since I develop not only at home but also at work, serving an Backend app in a specific language would slow down development due to app setup. I switched to Continuous Integration to speed up development while having all tech ready wherever I decide to code. I took the day off to search for a good and viable cloud solution for this issue.

**Link to work:** None

### Day 9: March 20th, 2017

**Today's Progress**: Played with Virtualmin to learn more about hosting management

**Thoughts:** I found myself using Google Cloud Engine because of their free plans and easy to setup workflow. Although their compute resources on free plan are pretty low (0.2 vCPU and 0.6Gb RAM), that was enough to set up an use case. If I could get to know Virtualmin better I could migrate to DigitalOcean as my main server hosting apps with Virtualmin. The outcome was positive.

**Link to work:** None

### Day 10: March 21th, 2017

**Today's Progress**: Struggled with CI solutions

**Thoughts:** After setting a VPS up, I went on choosing a CI solutions. There were plenty of them available (Travis, Codefresh, Codeship, AWS, etc.) but I had to find one that I could easily deploy to a custom VPS after building and testing steps. Travis were the most friendly UI that I found but still had some issues with custom deploy. Codeship offered the best solution with ready-to-use SSH deploy key and GitHub commit integration

**Link to work:** None

### Day 11: March 22th, 2017

**Today's Progress**: Setup Codeship CI 

**Thoughts:** There were some little things specific to CI that took me some time to learn like database integration, container images, env variables inside Laravel app, etc. I had to code custom scripts to set up the test steps and another one for custom deploy. I learned a bit from it all, interesting day.

**Link to work:** [Programming Diary API](https://github.com/rasouza/diary-api-php)

### Day 12: March 23th, 2017

**Today's Progress**: Wrote test cases and initiated Git-flow 

**Thoughts:** Now that every commit on master will trigger a new build on Codeship, I had to implement test cases to make sure that my code is working when automatic deploy runs. To make things easier, I started using git-flow to better manage branch features and releases.

**Link to work:** [Programming Diary API](https://github.com/rasouza/diary-api-php)

