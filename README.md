Important! - I am not the initiator of this project. It is made as a part of the React course. With permission of the author, I use it ONLY as an adition to my portfolio.

This is a simple application which shows 2 screens: 1 with movies, 2nd with watched movies. After draging movie to the watched list movies you can rate the movie and then add it to the list.

Application downloads datas from OMDB API. If you want to do it yourself just go the OMDB page and create your own API there since there is a requirment for using acc. I removed my Api in this app so you can put there generated by your own.

In order to work application correctly just use followed commands in console (since node_modules are added to gitignore)

1. "cd use-popcorn"
2. "npm install" or "npm i" (means the same)
3. "npm start" 
4. "don't forget about your API" (Tip: I created variable that stores personal generated key so you can just past the key there.)
Application is created in vanila React (CRA). There is no 3rd party libraries here.

Whats there then?

App inludes:
-Hooks like useState and useEffect (data fetching and some others side-effects)
-Handling events
-Fetching, downloading and showing data from API using async await functions
-handling some situations where you can get Error while sending requests
-A lot of child-parents relation
-Some Props-Drilling (I know, it's antypatern but It is made as a part of the course and excercises so i personaly prefer to do some mistakes here then later. After all We needs to know good practices and why we should't do props drilling. Maybe in future I will handle this with textContext)
