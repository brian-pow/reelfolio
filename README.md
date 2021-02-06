REELFOLIO is a place for filmmakers to come together, connect with other talent, showcase work and share content, and more. I developed the REELFOLIO beta and MVP versions in 2019. This included onboarding the first 200 users for testing and optimization on a fully-functional site. The project has since been taken on by a professional development team, and stands at www.reelfolio.com.

Although I cannot share the code base, wanted to drop a brief description of the site here to showcase some of my experience / capabilities.

**Usage of the site allowed for the following main activities:**
-Create a profile (like a Linkedin prof...but centered around film projects and other creative initiatives)
-View other profiles
-Post jobs
-Browse, search, and apply for jobs
-Post "posts" (i.e., sharing an interesting article) in a timeline-format

**Architecture:**
The backbone of the site is an Express (node.js) server. Each route accessed eventually responds with an EJS (Embedded JavaScript) template - close to vanilla HTML, but allows for insertion of variables from the server. MongoDB was used as the primary database, integrated with Express through Mongoose. Authentication was handled through Firebase Auth. Stripe was used to collect payment upon new member sign-up. Mailchimp was used throughout to send various e-mails (e.g., new applicant to one of your posted jobs).

**Screenshots:**

![Slide1](https://user-images.githubusercontent.com/42954670/107124260-68daf680-6868-11eb-98e7-6cd9a8852880.png)
![Slide2](https://user-images.githubusercontent.com/42954670/107124262-6b3d5080-6868-11eb-9c6a-af7330af282d.png)
