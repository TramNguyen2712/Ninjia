Ninjia Escape game is inspire by PacMan. We use the Unity to built the game with C# language. 
There are 2 characters we need to create for game - Ninjia and Enemy. Another, we can create the scores like counting the coins,
hearts also. 
Ninja run away the Enemy
Both Ninjia and Enemy need animation and movement.
We can use the keyboard to control direction of the player - left, right, up, down 
 
 movement.x = Input.GetAxisRaw("Horizontal");
 movement.y = Input.GetAxisRaw("Vertical");

And formula of moving

rb.MovePosition(rb.position + movement * moveSpeed * Time.fixedDeltaTime);

