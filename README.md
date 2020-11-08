# chat-example
This is a code sample that uses [Node.js](https://nodejs.org/) to show how to implement a [real-time](https://en.wikipedia.org/wiki/Real-time_computing) application.

This repo is based in the source code –for a very simple chat example– used for
the [Getting Started](http://socket.io/get-started/chat/) guide
of the Socket.IO website.

## how to use the code
Run the `npm start` command and go to the http://localhost:3000 address in your prefered browser. 
You can open more than one tab (or window) with the same address and you'll see the magic not only in the browser, I've implemented some log messages that will show you the users interactions.

## what about the code conventions?
For now we're working with a single linter definition based on [ESLint](https://eslint.org/docs/user-guide/getting-started) and our commit messages are using the [conventional commits](https://www.conventionalcommits.org/en/v1.0.0/#summary) rules.

## ideas to implement as soon as I can:
- [x] Add code conventions specs 
- [ ] Implement [husky](https://typicode.github.io/husky/#/) to enhace code conventions
- [ ] Implement CI workflow
- [ ] Deploy it in a real environment
- [ ] Implement CD workflow
- [ ] Add username and 'is typing' information according this [reference](https://livecodestream.dev/post/2020-07-11-a-starter-guide-to-building-real-time-applications-with-nodejs/)
- [ ] Replace jquery dependency for a new front end strategy
- [ ] Define how to make a distribuited version
- [ ] Define next steps
