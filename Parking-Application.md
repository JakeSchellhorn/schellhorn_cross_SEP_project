Our Application Requirements

## Functional Requirements
---

**Authentication** (priority 1)
1. As a user I want to be able to create an account so I can access various personal objects.
2. As a parking garage admin I want to be able to log in so I can edit my parking garages.
4. As a user I want it to be very easy to add and remove my card so it doesn't feel like a chore.

**User Interface** (priority 2) 
1. As a user I want the ability to claim a spot to be on the main menu so its straight to the point.
2. As a user I want the map api to use the android or apple maps depending on the device so it has a familiar feel.
3. As a user I want to have a menu item with all of my ticket history so I have a clear spot I can go back to.
4. As a parking garage admin I want to have a clean admin ui to set different parameters so its easy to change/set up.

**Notification System** (priority 3)
1. As a user I want the ability to opt in to notifications so I can see when my ticket expires.

**Promotional System** (priority 3)
1. As a user I want to be able to enter promotional code after buying a ticket on a ticket application to apply a discount to parking.

## Non-Functional Requirements
---

**Security** (priority 1)
1. As a parking garage we want all data transmitted between apps to be encrypted so we know data between is only accessed by people with keys.
2. As a user I want stripe to handle the payment system so I know its secure.

**Performance** (priority 2)
1. As a user I want the app to load within 5 seconds so there is no delay.
2. As a user I want the menu to be snappy and extremely responsive so there is no lag between input and action.
