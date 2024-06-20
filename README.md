# Blue Turtle

Blue Turtle is a tiny shell written in Go.
I needed a project for practicing my Go skills, therefore I was amazed when I found this short blog post: [Writing a simple shell in Go](https://blog.init-io.net/post/2018/07-01-go-unix-shell/).
After reading the post I extended the shell with some more advanced functionalities by myself.

{{**Video or Image**: It's always beneficial to showcase. Give them the result now instead of having them go to a website and then look for it.}}

## Contents

- [Features](#Features)
- [Tech Stack](#TechStack)
- [Process](#Process)
- [Learnings](#Learnings)
- [Improvement](#Improvement)
- [Running the Project](#RunningtheProject)

## Features
- Run commands
- Change directory
- Exit shell with exit command

<h2 name="TechStack">Tech Stack</h2>
- Go
- Some internal Go libraries

## Process
It was really easy to follow the blog article, because the author focused on simplicity.
Of course afterwards, when I started implementing my own features, it was way harder and I had to do some research.

## Learnings
I was amazed by how simple a shell could be!
The shell is one of these very intimidating looking technologies you encounter when you start programming, but now I feel like it can be very simple.
(Of course my shell is not comparable to zsh/bash feature set!)

<h2 name="RunningtheProject">Running the Project</h2>
You need to have Go installed. Then simple run the following command in the root directory of the project.
<code>go run src/main.go</code>
