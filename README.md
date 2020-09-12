# My Portfolio

## About

This portfolio website is built using a forked branch of [RyanFitzgerald/devportfolio](https://github.com/RyanFitzgerald/devportfolio)
project on github. It has been adapted with my information and skills, along with
some structural and visual changes.

The project has been Docker-ized and can be hosted within an nginx shell.

## License

This project uses the free MIT license as part of its fork. See [LICENSE.md](LICENSE.md) for more.

## Instructions

In order to setup the project, you will need Docker. Run the following docker commands:         
`docker build -t nldoty/portfolio .`      
`docker run -d -p 8080:3000 --name nldoty_portfolio nldoty/portfolio`
