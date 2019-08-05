# Angular Development

Welcome to our Angular development technical test.

First, if you are here it means that you are moving forward, this is good.
Now you have a chance to show us how good you are.

Before you start take a big breath and...

- Relax
- Take your time
- Quality above all else
- Be creative
- Surprise us

About the recruitment process...

- [x] HR Brief
- [x] **Technical test** (you are here)
- [ ] Manager Interview
- [ ] Tech Lead interview
- [ ] Job offer

## What to do

There will be a football tournament coming up, with 8 teams participating.  
The tournament will have 2 groups with 4 teams and playoffs (semi-finals and finals).

As the organizer of the tournament, I want to see the upcoming matches, set the results and see current standings.

### Features

- Matches
  - List of matches
  - Filter by team
  - Filter by date
  - Link to set final score
- Set score
  - Set the number of goals on each side
  - Ability to randomize score (using [API](https://www.random.org/integers/?num=2&min=0&max=5&col=1&base=10&format=plain) - see [Rules and Tips](#rules-and-tips))
  - Update standings
- Standings
  - Group grids
  - Teams wins, losses and points
- Playoffs
  - 2 top teams from each group should advance to playoffs
  - Winners in playoffs should move to the final
- Automated tests
  - Feel free to create the tests you find more suiting

## What NOT to do

- You don't need to create a Form for registering teams or matches, feel free to add 8 teams, split them in 2 groups, add the matches, dates, etc.
- Don't worry about the specifics of tournament rules, just define a rule in case of a tie in groups and in case of a tie in playoffs

## Rules and Tips

- Use **English** for everything
- Add all your code to the `src/` folder
- Use [git](https://git-scm.com/) for versioning. Commit often
- Use [Angular](https://angular.io/) (6 or later) as your JavaScript framework
  - Use at least one Async method for an API method call. Suggestion: Random score generator getting data from [this API](https://www.random.org/integers/?num=2&min=0&max=5&col=1&base=10&format=plain)
- Either use [Angular's native testing](https://angular.io/guide/testing) or a popular JS test framework, such as [Mocha](https://mochajs.org/), [Jest](https://jestjs.io/) or [Jasmine](https://jasmine.github.io/)
- You are allowed to use other libraries and framework for styling, features, etc... Such as...
  - [npm](https://www.npmjs.com/)
  - [gulp](https://gulpjs.com/)
  - [webpack](https://webpack.js.org/)
  - [bootstrap](https://getbootstrap.com/)
  - [sass](https://sass-lang.com/)
  - [sweetalert](https://sweetalert2.github.io/)
  - many others
