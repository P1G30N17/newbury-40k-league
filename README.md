# Newbury 40K League

The Newbury 40K League project is a basic webpage that allows new and returning players of the well known table top battle system Warhammer 40 000 to organise games in a fun, but semi competitive environment. The league system works by pairing players, who have enrolled in the current league, with other players from the league and keeps a record of their games to be tallied into a league leaderboard. Players will be able to find rules and information pertaining to the league as well as their opponents and regulary scheduled matches over the coarse of each league (generally 3 months). The project was designed from inception with responsiveness in mind and as seen below adjusts well on varying devices.

![Responsive Mockup](https://p1g30n17.github.io/newbury-40k-league/assets/readme-media/viewports.png)

## User Stories
- As someone new to 40K this site helped me find a local gaming club to fit my schedule.
- As a 40K player this site is great for matching me with similarly skilled players to test my tactics.
- As a 40 player I enjoyed using this site for friendly matchups, rather than me having to search forums to find other players.
- As a competitive player of 40K I found it very easy to submit my results from a league game and find out who my next opponent is.

## Features 

The following features are intended for all users both new and returning to be able to quickly and easily navigate the webpage to their desired effect. Returning users will be able to find the required information pertaining to their league standing and upcoming matches for the outlined month. Whereas new users may be drawn into joining the league through the enticing homepage and then apply to join the league via the necessary application process.

### Existing Features

- __Navigation Bar__

  - Featured on all pages (even pages that are not assocaited with the site structure, such as the submit results page or the league application page). 
  - This will allow the user to quickly navigate to a desired page, as well as indicate which page they are currently on via the nav tab being highlighted. 

![Nav Bar](https://p1g30n17.github.io/newbury-40k-league/assets/readme-media/navbar.png)

- __The landing page image__

  - The landing page image captures the user's attention with a game of Warhammer 40K in play.
  - This image captures most elements of a game of Warhammer 40K, player interaction, dice, miniature figurines and thematic scenery and board. 

![Landing Page](https://p1g30n17.github.io/newbury-40k-league/assets/readme-media/landing-image.png)

- __Why join a league? section__

  - This section pulls the user in with a well known 40K character, Abbadon the Despoiler and a Norn Emmissary, surrounded by text that conveys the question to the user, the benefits of joining a league. 
  - These statements will stand to answer the users question of why would they want to join a 40K league. 
  - The statements vary from a casual environment to someone with high degree of skill in playing 40K enabling the webpage to draw in both new and veteran players of Warhammer 40K.
  -This section is responsive in that on small screen the norn-emmissary image is removed and abbadon image is place at the bottom, as opposed to the 4 quadrant display on larger screens.

![Why join a league?](https://p1g30n17.github.io/newbury-40k-league/assets/readme-media/why-join.png)

- __The Footer__ 

  - The footer contains links to 3 different tabletop gaming clubs in and around Newbury, Berkshire, UK. These open in a new page when the Facebook icon is clicked. 
  - Let it be known that each footer link is a Facebook group, and as such the variation in social media is limited as the groups all operate on different days via their corresponding Facebook groups.
  -These Facebook links will help a user find a night and club that best suits their schedule.

![Footer](https://p1g30n17.github.io/newbury-40k-league/assets/readme-media/footer.png)

- __The League Page__

  - The league page is where both new and current users will navigate to, to find information pertaining to the current league standings and their league game matchups.
  - The page is basic in its design in that it conveys the exact specifics of what a user would need to determine their position in the league and who they have to play within the current month to score points on the leaderboard.
  - Below the league matchups are where a user would interact to navigate to their corresponding need of the website, either they would be submitting their results, or they would be applying to join the next league.
  - Let it be known that I would like this page to become a lot more advanced in the future, hopefully to include a responsive table that pulls results from a realtime database and updates the league standing and matchups automatically as opposed to manually entering the results and matchups for each month. 

![The League](https://p1g30n17.github.io/newbury-40k-league/assets/readme-media/the-league.png)

- __Submit Results Page__

  - This page allows the user to submit their league game results. 
  - It is extremely simple for the user to use, they simply select their name enter their victory points and then select who their opponent was and their opponent's victory points.
  - Currently the webpage just posts the information to the Code Institute form dump page and returns the values entered. In the future they will be posted to a database that would update the current league table in realtime.  
  - There is a waiver that the user must click with a hyperlink to the current newbury40kleague that users can read and gain more precise league rules from, as the current website owner Mark Laverty updates the rules via a poll held on facebook every few leagues. 
  - A future update could include a polling system on the site and a page for rules and information in a better layout.
  - A point to note is that a user can only access this page from The League page as future updates will allow for logged in users to be able to access this submission feature.

![The League](https://p1g30n17.github.io/newbury-40k-league/assets/readme-media/submit-results.png)

- __Apply for Next League Page__

  - This page allows the user to apply to join the next available league (leagues usually last 3 months). 
  - It is extremely simple for the user to use, they simply input their name and surname along with selecting their preffered faction they will be playing for the duration of the league from the dropdown menu.
  - Currently the webpage just posts the information to the Code Institute form dump page and returns the values entered. In the future they will be posted to a database that would update the current league matchups in realtime.  
  - A point to note is that a user can only access this page from The League page as future updates will allow for logged in users to be able to access this submission feature.
  - A future feature would be to allow users to join ongoing leagues and be allocated catch up games to point them in contention for the current leaderboard rankings.

  ![Apply for Next League](https://p1g30n17.github.io/newbury-40k-league/assets/readme-media/application.png)

  - __Gallery Page__

  - This page allows the user to view pictures from previous games of the league.
  - The page is responsive so as to allow larger screens to see more images at once, as opposed to a single column of photos for a smaller device user.
  - A future feature would be for league members to be able to submit photos of their games via email to the admin who would decide if the photos would be worthy for submission, such as child friendly and SFW (Safe for Work).

![The League](https://p1g30n17.github.io/newbury-40k-league/assets/readme-media/gallery.png)

### Features Left to Implement

- User Login.
- Results submission to a realtime database.
- League table updates pulled from the above realtime database.
- Catchup game mechanic for new users wishing to join an ongoing league season.
- User photo submissions from league games.
- Add a rules and information page once the old newbury40kleague.com webpage is phased out, with updated and streamlined information, along with a potential polling system for league rules and costs. (currently the league is free)

## Testing 

- The Newbury 40K League project was tested on the following devices: Desktop pc (1920 x 1080), iPad Air (2360 x 1640) and iPhone XR (1792 × 828) along with the Google Chrome inspect tool for responive dimension testing.
- The Newbury 40K League project was tested on the following web browsers: Google Chrome, Microsoft Edge and Mozilla Firefox.

### Device Testing
- The project is responsive in almost all dimensions bar a few outliers such as a smart watch.
- This was done by multiple commits and adjustments throughout the project inception to incorporate a wide array of dimensions, this mainly including allowing the text and information to nicely nest on the page for the user in a clear and coherent manor.

![Responsive Mockup](https://p1g30n17.github.io/newbury-40k-league/assets/readme-media/viewports.png)

### Web Browser Testing

- The project obtained a decent lighthouse rating with the Google Lighthouse Dev Tool, however future code could be implemented to allow the images to load faster as that seems to be pulling the overall score down.

![Lighthouse Score](https://p1g30n17.github.io/newbury-40k-league/assets/readme-media/lighthouse.png)

- The various web browsers the project was tested on had mostly optimal results, with little to no errors between all 3.

### Page Testing

- I have checked that all the navbar links work correctly and take the user to the correct pages.
- I have checked that all submission buttons are active and submit the user's input to the Code Institute form dump page with the correct attributes.
- I have checked that all user input requests are correct, and inform the user when an input request is incorrect or empty.

### Bugs

- When testing the project in Mozilla Firefox I encountered an error when trying to remove the number spinner from the number input request on the Submit Results page, I used the following code to solve the problem:
- #submit-results-form input[type='number'] {
    -moz-appearance: textfield;
}

### Validator Testing 

- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/)
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/)

### Unfixed Bugs

- None. 

## Deployment

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

The live link can be found here - https://p1g30n17.github.io/newbury-40k-league/ 


## Credits 

### Code

- Table generated using TableGenerator (https://www.tablesgenerator.com/)
- Coding assisstance and reference taken from the Love Running Tutorial project from Code Institute.

### Media 

- Terminator by Robert Bjurshagen from <a href="https://thenounproject.com/browse/icons/term/terminator/" target="_blank" title="Terminator Icons">Noun Project</a> (CC BY 3.0)
- Photos by page owner (James King)

### Content 

- The original website was an inspiration to create a more reactive project and I have the owner (Mark Laverty)'s full permission to implement a new and improved website to further benefit our 40K League. Original <a href="https://www.newbury40kleague.uk/" target="_blank" title="Newbury40KLeague">webpage</a>
- There is no claims or copyright infringement with the name Newbury 40K League.
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)

