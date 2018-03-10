# ButtonTransferApp
A simple Android app that uses a REST-ful API. The app allows "Money" transfers between user's created by a Candidate ID.

# MainActivity 

Displays a list of users created by a specific candidate. The cardView contains the name, email and ID of each user. When you click the start Transfer button it brings to another Activity. When this button is clicked the User's information (ID and Name) is passed to the Transfer Detail activity. This page also has a option menu button , when clicked it opens to a new activity and allows you to enter information about the new user.

![mainactivity](https://user-images.githubusercontent.com/22303069/37234710-3dceec4e-23f1-11e8-8d63-9d692f30993c.png)


# Add a new user

You can add a new user by entering the new user information. Once the "Add" button is clicked it will take you back to the List of user's with the updated list. 

![add person](https://user-images.githubusercontent.com/22303069/37234714-441544ea-23f1-11e8-9059-c59d32e6acf4.png)

# TransferActivity 

This activity Displays the current user's name and allows you to transfer amounts from current user displayed to another user. There is a dropdown list that shows all available user's to transfer "amounts" too.

![transactions](https://user-images.githubusercontent.com/22303069/37236010-8d3071f4-23fb-11e8-8026-884586e6f7ca.png)










