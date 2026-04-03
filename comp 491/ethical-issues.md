# Ethical Issues
Our app tracks workouts and water intake and turns that data into progress for an RPG character. Because the app stores some personal information, we need to think about how user data is handled.

## User Privacy
Users expect their workout data and account information to remain private.
  - Passwords are encrypted using bcrypt
  - User data is stored in MongoDB Atlas
  - Users can only access their own account information
  
## Fairness and Bias
The system treats all users the same.
  - Character progression is based only on workouts and activity
    
## Preventing Misuse
Some users may try to cheat, to reduce this we have.
  - Character stats are calculated on the server
  - The system validates workout data before saving it
