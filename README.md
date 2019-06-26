# What is this repo?
This repo has UI designs for the [Mole project](https://github.com/davrodpin/mole), from [David Pinheiro](https://github.com/davrodpin/) and others.

## What is Mole?

Mole is: <blockquote>"a cli application to create ssh tunnels, forwarding a local port to a remote endpoint through a ssh server."</blockquote>

You can find [documentation on how it works](https://davrodpin.github.io/mole/).

I'm interested in the project as a nice way to configure SSH tunnels on my Linux machine.

Also, I'd like to do some design work. :)

## Designs

These designs are made using Balsamiq. I know. It's not open source.

Balsamiq supports versioning *in the application* - each .bmpr file can have 1) multiple designs, and 2) multiple versions (what they call "alternate" versions) of each design.

It doesn't support versioning with individual files well. (If I'm wrong, please correct me)

This basically means, to see each version of each design you need to have Balsamiq, *or* you/I have to export each design version to a .png.

## User research

- [Hackernew thread](https://news.ycombinator.com/item?id=18236125) about Mole

## Design to-do list

- [x] create ssh aliases
- [x] create local-remote ssh tunnels
- [x] way to connect/disconnect ssh tunnels
- [ ] need way for user to enter multiple local:port + remote:port combinations
- [ ] create remote-local ssh tunnels
- [ ] auto-select local port
- [ ] add ssh-key path for each tunnel
- [ ] add ssh password for each tunnel
- Options, to include:
- General
 * [ ] start mole in background
 * [ ] use ssh config file parameters
-  Specific tunnel options
 * [ ] skip host key validation
 * [ ] configure server connection timeout. Detailed in [GH issue 12](https://github.com/davrodpin/mole/issues/12).
 - Server reconnect
 * [ ] configure "server reconnect" if connection it drops. Detailed in [GH issue 24](https://github.com/davrodpin/mole/issues/24). (default on)
 * [ ] configure time to wait before server reconnect
 * [ ] configure number of reconnect retry attempts before giving up
 - Keep alive
 * [ ] configure "keep alive" . Detailed in [GH issue 24](https://github.com/davrodpin/mole/issues/26). (default on)
  * [ ] configure persistent ssh connection. Detailed in [GH issue 26](https://github.com/davrodpin/mole/issues/26). (default send packet every 10s, allow user to change)
- [ ] add more things to this to-do list!
- [ ] add way to view tunnel logs

## Want to help?

### 1. Get Mole running

[Install details](https://github.com/davrodpin/mole/blob/master/README.md) are in the main repo.

### 2. Look at the docs

[The documentation](https://davrodpin.github.io/mole/) is probably a good place to start.

### 3. Look for a design issue

The [Issues are located in David's repo](https://github.com/davrodpin/mole/issues). Have a look there for some design tickets.

### 4. Get in touch

- twitter: @bernardtyers
- email: bernardtyers@acm.org

## License

These designs are licensed, like the Mole project, under MIT License.
