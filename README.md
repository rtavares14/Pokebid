# Welcome to My Auction Website!

Here, I will explain some of the features I've implemented, the reasons behind them:

## Some Features I've Implemented

### 1. Random Auctions on the Main Page

- Each time you visit the main page, you'll see 5 random auctions. This encourages users to explore different items.
- To view all available auctions, you will need to log in and go to the cards page.

### 2. Bidding Rules

- Only users who are not admins can place bids.
- To prevent conflicts, users cannot bid on their own auctions.
- Users cannot bid more than 30% above the highest bid.
- After a user places a bid, they will need to wait for another user to bid before they can bid again.

### 3. Validation for Auctions

- When creating or editing an auction, I've implemented various checks to ensure everything is correct.
- For example, if an image link for a card is broken, the system will automatically replace it with a default image
  instead of showing an error.
- Auctions cannot have a start date that is after the end date.
- Once an auction has ended, it cannot be edited.
- While an auction is live, you cannot change the starting date or price.
- Changes can only be made before the auction starts.

## Testing order

- For my tests to work, you will need to run the backend first and then the frontend (but i have a filling that you know
  that already).
- As you asked I made a test order
- First run my [Token test](tests/rest/tests/token.http)
- Then run my [User test](tests/rest/tests/user.http)
- And for last run my [Cards test](tests/rest/tests/cards.http)

## To Run the Project

1. Clone the repository.
2. Navigate to the project directory.
3. Run the backend server using npm i and npm start.
4. Run the frontend server using npm i and npm start.
5. Open your browser and go to referenced URL.
