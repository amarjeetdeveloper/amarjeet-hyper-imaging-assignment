# amarjeet-hyper-imaging-assignment
hyper imaging assignment made by amarjeet

Roringo Challenge
1. Get free postgres using Supabase.com and execute the following SQL to setup tables
and seed data into these tables
https://sqlize.online/sql/psql14/f817007d71dab1919c27bd9521da0616/
2. Setup a NextJS application with the following specifications
a. As soon as user loads home page, create a profile for user with a random
generated uuid and use window.prompt() to get user name. Save into cookie
using next-session package. If user clears cookies then they will lose their
account.
b. Root Path (/auctions) of the application should show:
List of available auctions (select auctions and join with item to get the display
details)
c. /auctions/[auction_id] page should show:
The details of the auction by auction_id (select auction and join with item to get
basic info)
- Name, image, description
- Quantity
- Previous bids (select bids by auction_id and join with profile_id to get user
details) ordered by most recent first
- Button to place a bid
- On button click use window.prompt() to get a new value and
create a bid
What is expected: Github repository with the code for the NextJS application
3. Deploy this NextJS application to Vercel using Github connection
https://nextjs.org/learn/basics/deploying-nextjs-app/deploy
What is expected: A URL the deployed AP
