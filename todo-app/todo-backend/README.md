# Express application

Install dependencies with `npm install`

Run with `npm start`

Or in development mode with `npm run dev`

# Visit counter

When running the server, visit http://localhost:3000 to see visit counter, or give environment variable `PORT` to change the port.

# MongoDB

The application has /todos crud which requires a MongoDB. Pass connection url with env `MONGO_URL`

# Redis

Pass connection url with env `REDIS_URL`

# Excercises

12.5.1  - OK (rakennettu docker build -t todo-backend-image . --> docker run -p 3123:3000 todo-backend-image)
12.5.2  - OK (http://localhost:3123/)
12.6    - OK (yml tehty. ajettu komennolla: docker compose up ja saatu counter selaimeen localhost:3000)