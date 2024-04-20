

# Node-Clone Twitter

Node-Clone Twitter is a simple Twitter-like application built with Node.js, Express.js, MongoDB, and Mongoose. It allows users to register, log in, create tweets, follow other users, view tweets from followed users, and interact with tweets by liking or disliking them.

## Features

- **User Authentication**: Users can register an account and log in securely.
- **Tweet Creation**: Logged-in users can create tweets with a description.
- **Following Users**: Users can follow other users to see their tweets in their timeline.
- **Timeline**: Users can view tweets from users they are following in their timeline.
- **Interactions**: Users can like or dislike tweets.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/fahad0samara/node-clone-twitter.git
   ```

2. Install dependencies:

   ```bash
   cd node-clone-twitter
   npm install
   ```

3. Set up environment variables:

   Create a `.env` file in the root directory and add the following variables:

   ```plaintext
   MONGO_URI=<your_mongodb_uri>
   TOKEN_SECRET=<your_token_secret>
   ```

4. Start the server:

   ```bash
   npm start
   ```

## Usage

- Register a new account or log in with existing credentials.
- Create tweets by clicking on the "Create Tweet" button and entering a description.
- Follow other users to see their tweets in your timeline.
- Interact with tweets by liking or disliking them.
- Log out when you're done.

## Contributing

Contributions are welcome! If you find any bugs or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

---
