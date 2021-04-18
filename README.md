# multiplayerSnake
Code for multiplayer snake game with [socket.io tutorial](https://www.youtube.com/watch?v=ppcBIHv_ZPs) on the Traversy Media YouTube channel.

If you want to see how to deploy the game check out [this video](https://www.youtube.com/watch?v=M9RDYkFs-EQ)


$ heroku login
$ heroku create
$ heroku features:enable http-session-affinity (see why here: https://www.youtube.com/watch?v=M9RDYkFs-EQ)
Go to deploy and connect via Github
Go to settings and add build pack:
- (paste in as url) https://github.com/timanovsky/subdir-heroku-buildpack
- nodejs
Press Reveal Config Vars and add Config var:
key: "PROJECT_PATH"
value: "server" (or name of the subfolder)

Ticket url
https://help.heroku.com/sharing/9bc23cd0-ae42-4a5e-a204-519bbee6fa91