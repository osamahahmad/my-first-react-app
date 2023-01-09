# my-first-react-app
This is a repository for my third Node.js project: my first React app. I'm becoming adjusted to Node projects using [`express`](https://www.npmjs.com/package/express) to serve web content, and I'm ready to start developing a modern front-end.

## Creating the React project
This was an extremely simple task:
```
npx create-react-app my-first-react-app
```
I then generated a license file, a relevant .gitignore and a Contributor Covenenant:
```
cd my-first-react-app
npx license
```
```
npx gitignore node
npx covgen me@osamahahmad.com
```

Testing my app is simple with `npm run test`.

## Creating the web server
I used `npm` to install `express` in the React project directory:
```
npm install express
```
`express` is the most popular Node web framework, and I can use it to serve a "my-first-react-app/build", generated using `npm run build`.
