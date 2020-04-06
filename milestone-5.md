# Project Milestone 5

## Testing Plan

We will run automated tests when we can to find things like lint errors, but otherwise the tests will be manual QA tests. We hope that by manually testing we will find issues that we wouldn't find with automated testing such as UX issues and design issues. We are looking into Jasmine and Grunt for automated testing.

## Sign In & Sign Up Testing

- [ ] User should be able to sign up with an email and password.
- [ ] User should not be able to have a password with fewer than eight characters.
- [ ] Email and password should be stored in our database.
- [ ] User is able to sign out and then sign back in.

## Game Movement Testing

- [ ] User should be able to move their character around the game room.
- [ ] User should not be able to lose their character.
- [ ] User should not be able to "go into" objects. In other words, their character should collide with objects like tables.

## Gameplay Testing

- [ ] User should be able to "enter" (play) any game.
- [ ] Game behaves as in real life. That is, the game logic is correct. No bugs.
- [ ] User should be able to exit game without any bugs even if the game is not finished.

## Stats Testing

- [ ] User should be able to view their wins and losses.
- [ ] User should be able to see how many points they have.

## Inventory/Store Testing

- [ ] User should be able to view their inventory.
- [ ] User should be able to purchased new items using their points.
- [ ] Purchased items enter their inventory, and their points are appropriately reduced.