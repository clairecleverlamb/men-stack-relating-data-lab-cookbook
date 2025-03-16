# Cookbook - A Pantry Tracker

![pantry-interface](public/pantry.png)

**A comprehensive inventory tracking app designed to help users manage their pantry while engaging with the community for inspiration.**

## 🌟 Features
- **User Authentication:** Securely sign up, sign in, and manage pantry items.
- **Community Engagement:** Browse and explore other users' pantries for new ideas.
- **Personal Pantry Management:** Add, edit, and remove food items from your inventory.
- **View Other Pantries:** Click on a user profile to see their pantry items.
- **Simple & Responsive UI:** Built using EJS templates and CSS for a clean user experience.


## 🛠 Tech Stack
- **Backend:** Node.js, Express, MongoDB, Mongoose
- **Frontend:** EJS, CSS, JavaScript
- **Authentication:** Express-session for secure user login

## 📂 Folder Structure
```
/public         # Static assets (CSS, images)
/views          # EJS templates for pages
/controllers    # Route handlers for users, auth, and food items
/models         # Mongoose schemas defining database structure
/middleware     # Authentication & user session helpers
```

## 🏗️ How It Works

### User Flow
1. **Sign Up & Sign In:** Users create an account and log in.
2. **Manage Pantry:** Users can add, edit, and delete items from their pantry.
3. **Explore Community:** A dedicated page allows users to view others and their pantry items.
4. **View Other Users’ Pantries:** Click on a username to see what they have stored.

### Key Routes
| Method | Route | Description |
|--------|----------------|-------------------------|
| GET | `/` | Homepage |
| GET | `/users` | Community page with all users |
| GET | `/users/:id` | View specific user's pantry |
| GET | `/users/:id/foods` | See all food items for a user |
| POST | `/auth/sign-in` | User login |
| POST | `/auth/sign-up` | User registration |
| POST | `/foods` | Add a new pantry item |
| DELETE | `/foods/:id` | Remove an item |

## 📌 Future Enhancements
- 📊 **Analytics Dashboard:** Track pantry usage trends.
- 📆 **Expiration Date Reminders:** Notify users before items expire.
- 📸 **Image Uploads:** Allow users to upload food item pictures.
- 📢 **Community Forum:** Users can share recipes and tips.

---


