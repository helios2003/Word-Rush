# Word-Rush
Word-Rush is a multiplayer real-time Wordle game where users can register themselves on the platform and join in to play simultaneously with other participants. Players can generate invite links to share with others and compete to guess the generated word. The game ensures that all participants in a group are presented with the exact same word to guess. 
## Instructions for Setting up the repository
* Clone the repository using the command
```
git clone https://github.com/Devaansh-Kumar/Word-Rush.git
```
* Or alternatively create a fork of the repository with the command
```
git clone https://github.com/<your-username>/Word-Rush.git
```
### Frontend
1. Navigate to `client` directory and run `npm i` to install the necessary packages.
2. Run it using `npm run dev`.
3. Frontend runs on `http://localhost:5173`.
### Backend
* Navigate to `server` directory.
#### Env
1. Touch a file `.env`.
2. Duplicate the `.env.example` file and rename it to `.env`.
3. Fill in the necessary environment variables in the `.env` file and start the database.
#### Run the Backend
1. Run `npm i` to install the neccessary packages.
2. Run it using `npm run devStart`.
3. It runs on `http://localhost:3000`.

## Tech Stack
1. MERN Stack (MongoDB, Express.js, React.js, Node.js)
2. Tailwind CSS
3. Socket.io

## References
1. https://react.dev/learn
2. https://v2.tailwindcss.com/docs
3. https://socket.io/docs/v4/
4. https://blog.bitsrc.io/apis-vs-websockets-vs-webhooks-what-to-choose-5942b73aeb9b
5. https://dev.to/nitdgplug/learn-the-basics-of-socket-io-by-making-a-multiplayer-game-394g
6. https://medium.com/@RossWhitehouse/setting-up-eslint-in-react-c20015ef35f7