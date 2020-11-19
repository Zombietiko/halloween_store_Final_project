<h1>The Halloween Store| Full Stack Frameworks with Django Milestone Project  </H1>

Please click [here](https://hsstore.herokuapp.com/) to visit a live demo of my project.

My final Milestone Project for Code Institute is a Django Fullstack app.
app my idea is to create a The design was to have an app for a Halloween store.

<H1>UX</H1> 

<h2>Who is the target audience?</h2>

A person who is interested in Halloween.
A person who wants to find items for a Halloween Party.
A person who wantes to scary items.

<h2>Why is this the best way to target the audience?</h2>

The app is designed to lead the user to buy various Halloween items.
The app is designed to lead the user to create an account with the Halloween Store.
The app is designed to lead the user to buy various items.
The app is designed to lead the user to interact if they want to leave a review about the product they bought..

<h2>User Stories</h2>

<p>•As a user, I want to find products for Halloween.</P>
<p>•As a user, I want to add my reviews.</p>
<p>•As a user, I want to be able to bu various products for my Halloween Party.</p>
<p>•As a user, I want to be able to see my order history.</p>
<p>•As a user, I want to be able to be able to print my order history.</p>

<h2>UX Design</h2>

The UX Designs of the site can be found in the PDF file saved to the project in the file UX Designs.

<h1>Technologies</h1>

<p>•Html</p>
<p>•CSS</P>
<p>•Gitpod - Used for a development and testing area.</P>
<p>•Django</P>
<p>•Pillow - for images in the site when using Django</p>
<p>•Postgres - via Heroku</P>
<p>•Stripe -  For payment details</p>
<p>•Heroku - Connected to my Git repositoty to deploy app.</P>
<p>•git- Used as a repository.</P>
<p>•Bootstrap - Bootstrap framework.</P>
<p>•jQuery.</P>

<h1> Features </h1>

<h1>App logic</h1>

The app logic leads the customer to sign up to the site and buy items for Halloween.

<h1>Cross-app logic</h1> 

The app works on a mobile via a web browsers.

<h1>E-commerce</h1>

As the app is a store, It has items and prices detailed thoughout the site to add items to the basket and to purchase when finished shopping. 

<h1>Authentication and Security</h1>

The app has a sign up and login fucntion and the user can only pay for item after they have paid 

<h1> Testing </h1>

<p>•I tested the navbar in the chrome browser to ensure that all sections went to the relevant pages.</P> 
<p>•I tested that all the product images would add to the homepage.</P>
<p>•I tested that all the categories went to the right product sections.</P>
<p>•I tested the images displaying in all pages when clicked on would go to a larger version of the prduct.</P>
<p>•I tested when the prodcuct loaded that you had to either login or sign up to be able to add the product to the cart.</P>
<p>•I tested that that sign in and sign up options worked</P>
<p>•I tested that that the order history, would display in the welcome back drop down after you the used had logged in</P>
<p>•I tested that that the when adding a product to buy it appeared in the cart.</P>
<p>•I tested that that the payment options (stripe) all worked when making a dummy payment for the product.</P>
<p>•I tested that after the purchased was completed that the stock would deplete to ensure the right number of units where displaying</P>
<p>•I tested that the user can add a review when logged into the app</P>
<p>•I tested that the user could print off their invoice if they wanted to for their records</P>
<p>•I tested that the categories and products in Django admin went into my app</p>
<p>•I tested that that the search function worked and loaded the product that I had added</P>
<p>•I Used W3c validator to validate the html pages created. I copied my code and pasted it into the validator to check for errors and warnings.</P>
<p>•I tested that Heroku had connected properly with my git repository </P>

<h1> Deployment </h1>

1. Make sure requirements.txt and Procfile exist:
`pip3 freeze --local requirements.txt`
`echo web: python app.py > Procfile`
2. Create Heroku App,login to heroku (Heroku login), 
git init, connect git to heroku (heroku git remote -a <project>), 
git add ., git commit, git push heroku master.
3. heroku ps:scale web=1


<h2>Media</h2>

<p>https://www.funidelia.co.uk - Images  for costumes </p>
<p>https://www.poundland.co.uk - Images for makeup and props</p>
<p>https://www.coop.co.uk - Images for chocolates and sweets</p>


