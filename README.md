# rackapp_sample_purry

A simple rack frame work to generate static websites. 

Best to host it on heroku(foc) and link it to a domain. 

Follow the steps below upon clonning the app :-

1. Bundle install

2. Place css/html/javascript codes in the relevant folders. Index.html is where you place the index codes.

3. To run locally :- 
   Go to  your console 
    - $cd site 
    - Directory should be at Site Root Directory e.g /Users/Documents/rackapp_sample_purry/site
    - $rackup
    - copy the localhost link to your browser e.g http://localhost:9292/
    
4. Hosting your website/ Deploy to Heroku
  - Before deploying ensure that heroku toolbelt has been install and you have an account with them , if haven't install it here https://toolbelt.heroku.com/
   and do the necessary configuration. Don't worry it's easy.
  - Directory should be at Site Root Directory e.g /Users/Documents/rackapp_sample_purry/site
  - Execute the commands below on your console step by step to deploy to Heroku 
  $ git init
  $ heroku create
  $ git add .
  $ git commit -m "Initial static site template app"
  $ git push heroku master
  
  At this point your site is deployed to Heroku and has been given an auto-generated URL. Open your site using the heroku open command:
  $ heroku open
  
  
5. In the event you were to have changes on your file locally, all you have to do is commit the changes and push like below:- 
  $ git commit "Updating static website"
  $ git push heroku master
  
