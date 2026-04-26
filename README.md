# labtes-2

go to folder from terminal and do,
  git clone ...
to go to vs code
  code .
in vs code terminal do - npm create vite@latest
create backend folder in normal way and in backend terminal - npm init -y
  npm install mongoose express cors dotenv
  npm install nodemon --save-dev

    ---update codes
    --backend .env PORT=5001
  in frontend terminal - npm install axios
  in backend package.json - "script"
    "start":"node server.js",
    "dev":"nodemon server.js"

  go to frontend .gitignore and copy and paste to backend
  --in vs code do generate commit and sync changes


  --frontend-vervcel
    add new-project-go to git frontend google url --paste to deploy
    -copy deployment url and paste in.env-vite_api_url

  --frontend .gitignore
  node_modules , .env, dist

  --backend ..
   node_modules , .env

   --in mongo url 
   mongodb+srv://admin:**1234**@cluster0.gzxjzax.mongodb.net/**wmt**?appName=Cluster0

   in vercel variables add vite_api_url =And https:// railway link /api
   root directory-frontend
