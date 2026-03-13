# Product Brief

## Product
A barter marketplace where users list items and exchange item-for-item, with optional cash top-up if values do not match.

## Core goals
- make barter exchanges easier to discover and negotiate
- support multi-vendor listings
- allow users to send and receive swap offers
- support messaging and offer negotiation
- support optional payment adjustment for unequal trades
- support logistics through shipping label generation

## Initial assumptions
- start with website first
- responsive web experience
- account-based marketplace
- trust and safety are important
- shipping labels likely require future integration with carrier APIs

## Core user flows
1. user signs up
2. user lists an item
3. another user discovers the listing
4. another user proposes an item swap
5. one side adds optional cash top-up
6. both sides negotiate in chat
7. trade is accepted
8. shipping labels are generated
9. shipment tracking / confirmation happens
10. exchange closes

## MVP features
- landing page
- user auth
- listing creation
- browse/search listings
- swap offer flow
- chat / negotiation thread
- cash top-up field in offer flow
- trade confirmation state
- shipping label generation placeholder flow
- dashboard for active exchanges

## Risks / open questions
- escrow model for cash top-ups
- dispute handling
- shipping carrier choice
- geographic scope
