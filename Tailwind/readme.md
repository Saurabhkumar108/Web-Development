install  node 
check node version node - v
setup  project npm init -y
npm install -D tailwindcss
npx tailwindcss init
change tailwind.config.js: content: [*.html]
create index.html file

create index.css file
add these line to index.css file
    @tailwind base;
    @tailwind components;
    @tailwind utilities;

add css link in your index.html file
<link href="./styles.css" rel="stylesheet">
generate styles.css from index.css, by executing the below command
    npx tailwindcss -i index.css -o ./styles.css --watch