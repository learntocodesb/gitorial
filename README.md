# git Tutorial

## Instructions
Follow these one step at a time, swapping in a new driver and navigator each time.

Before moving on to each new step,

1. Review what's new (`git status`)
2. Refactor if needed
2. Commit (combination of `git add <file>`, `git status`, `git diff`, `git commit -m '<description of code change>'`)

## 1. Bird Profiles
There is a row of sample text. Let's list some of our beautiful birds
so the world can see our majestic parrot collection!

The `img` folder contains 7 parrot pictures, named `parrot1.jpg`, 2, 3, etc. Add the first 3 parrots to the index page. Include their name and picture.

Their names are:
Lester
Pepe
Pete

## 2. Image size
The images don't quite look right. Let's get some consistency and clean this up! Open up `css/main.css` and set a uniform `width` to the bird images.

## 3. More rows
Add more rows (3 profiles per row) as needed to add the remaining birds' profiles.

Parrot 4-7's names are:
Sunny
Paco
Tweety
Louie

## 4. Bird Price
Exotic birds aren't cheap! Add the birds' prices to each bird's listing. Which html element makes the most sense?

*Prices*:

Lester - $45
Pepe   - $30
Pete   - $170
Sunny  - $50
Paco   - $100
Tweety - $45
Louie  - $50

## 5. Supplies
Create a `supplies.html` file that is a copy of `index.html`. Link to the supplies page from the index page.

## 6. Supplies
The products names and prices are:

- Wood Ring - $5
- Food Puzzle - $6
- Pirate Parrot Bridge - $12
- Ring Game - $6
- Parrot Perch - $40

# Extra Credit

## How would you improve it?
Pick a product owner from the group to figure out what the Polly Parrot Co customers want! Take a minute to create a backlog, and work down the list. Keep the backlog in priority order.

Create a branch and commit some tweaks with small, logical commits. When you're done with a set of tweaks, flip back to the master branch and see how it compares! Do you notice anything that could be better when you look at how it's changed?

You'll need the following commands:

`git chcekout -b <new_branch_name>`
`git checkout <existing_branch>`
