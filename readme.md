CHANGELOG
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