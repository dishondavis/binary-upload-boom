# Group Running App
  - CRUD and Authentication

---

# Install

`npm install`

---

# Things to add

- Create a `.env` file and add the following as `key = value`
  - PORT = 2121 (can be any port example: 3000)
  - DB_STRING = `your database URI`
  - CLOUD_NAME = `your cloudinary cloud name`
  - API_KEY = `your cloudinary api key`
  - API_SECRET = `your cloudinary api secret`

---

# Run

`npm start`

---

# MVP

  - C - (CREATE) ----> /POST: A logged in user can create post with <br> 
                              time, day, and start location of the run.
  - R - (READ) -------> /GET: Retrieving the post data to display to all users
  - U - (UPDATE) -----> /PUT: Can update the time, day, and location.
  - D - (DELETE) --> /DELETE: Delete the post for a run created, <br>
                              based on the user that posted the run. 

---

# Second Version

  - U - (UPDATE) -----> /PUT: Adding runners (users) to a specific POST. <br>
                              The new posts will have to include a runners field <br>
                              in the models schema. Possibly an array of strings or ids?
  - D - (DELETE) --> /DELETE: Delete a logged in user from a POST run they signed up for.
