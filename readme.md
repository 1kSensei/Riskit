CHANGELOG

Core:
- [x] Added cool loading animation instead of hoping your internet works

Blackjack:
- [x] Add CSS for card animations (slide from top)
- [x] Add message div in HTML
- [x] Modify drawCard to handle faced-down cards for dealer
- [x] Update deal() to deal faced-down second card to dealer
- [x] Update stand() to reveal dealer's second card and replace alerts with message text
- [x] Update checkBlackjack() to use message instead of alert
- [x] Update hit() to use message for bust
- [x] Add calculateVisibleDealerScore() function to compute score of only the first dealer card
- [x] Modify updateScores() to display visible dealer score when a card is face down, full score otherwise
- [x] Ensure stand() updates dealer score display after revealing the face-down card

Plinko:
- [x] Define peg positions in an array for collision detection.
- [x] Add gravity acceleration to dy in the animation loop.  
- [x] Implement peg collision detection: check distance to each peg, if colliding, adjust velocities (reduce speed, add random direction).
- [x] Add boundary collision: prevent ball from going out left/right by reversing and damping dx.
- [x] Test the changes to ensure ball behaves realistically and stays in bounds.

Coin:
- [x] Added cool flipping animation

Slots:
- [x] Added Slot spinning animation
- [x] Added stop buttons under each slot
- [x] Raised stakes