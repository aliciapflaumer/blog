---
layout: post
title:  "Project: Learning React with the game of Tic-Tac-Toe"
date:   2018-03-04 21:00:00
categories: web development
---

![Screenshot of tic-tac-toe game]({{ "/assets/screencapture-learning-react-ticTacToe.png" | absolute_url }}) <br>
*This is a Tic-Tac-Toe game built with ReactJS.*

The next project on my list of new tech that I wanted to become more familiar with and learn is React. I have been seeing it as yet another hot skill to know. So, of course, the first place I go to in my search for knowledge is the [React website][react-site].

I started off with reading through the [quick start guide documentation][hello-world]. React is component-based... like Angular. It uses ES6 syntax, such as, `arrow functions`, `classes`, `template literals`, `const`, and `let` statements. I learned about JSX, rendering elements, components, and props. I've learned that HTML is written within the JavaScript code, so that can be something to get used to. *For example:*
```
function Square(props) {
  return (
    <button className="square" onClick={props.onClick}>
    {props.value}
    </button>
  );
}
```

Jumping into the [tutorial][react-tutorial] which uses a simple Tic-Tac-Toe game, I wanted to build this on my local machine, opposed to using the alternative method in CodePen, and also learn how to install React. I followed along with the installation instructions to create my new app, which seemed easy enough.

There are really only two files that I created myself for the tic-tac-toe tutorial: `index.css` and `index.js`, the rest is created for me during the `npm install` installation process with `create-react-app`.

I've gone through the entire tutorial and I can't say that I'm completely comfortable using React on a new project of my own. But I have an idea of the workflow, like everything that is learned it'll take some repetition, and some real-world experience is the best way to learn new tech.

I went through the deployment steps as well, which weren't to bad. It is deployed on gh-pages [here][deployed-game].

At the end of the tutorial, there are suggested additions that one might want to try to continue learning.

What I would like to work on next:
1. When there is a tie in the game, let that display to the user.
2. When someone wins, highlight the row of the 3 squares.
3. When no one wins, display the result as a draw.

If you want to check out my code, you can see it on my [Github repo][github-repo]. I wrote frequent and thorough commits, from start to finish, to have a track record of my process.

[react-site]: https://reactjs.org/
[hello-world]: https://reactjs.org/docs/hello-world.html
[react-tutorial]: https://reactjs.org/tutorial/tutorial.html
[deployed-game]: https://aliciapflaumer.github.io/learning-react/
[github-repo]: https://github.com/aliciapflaumer/learning-react
