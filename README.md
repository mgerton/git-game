# The hg committer guessing game!

## What is it?

In the hg game, you  guess who made a commit to your team's repo based on their commit message:

![](https://cloud.githubusercontent.com/assets/21294/6098511/fb347c1e-afae-11e4-9152-5a132a10c3b3.png)

The goal is to get the longest streak! (It's harder than you think...)

## How do I play?

- [Download the `hg-game` executable](https://github.com/mgerton/hg-game/releases/tag/1.1)
- Put it somewhere on your PATH (like `/usr/local/bin`)
- Then, in any hg repository, run `hg game`
- (If you'd like, you can select a subset of commits, for example, `hg game --after={2014-08-08}`. For more options, see [http://hgbook.red-bean.com/read/customizing-the-output-of-mercurial.html](http://hgbook.red-bean.com/read/customizing-the-output-of-mercurial.html).)

## Requirements

- Requires Ruby >1.8

## "I can't get it to work", "It would be cool if you could...", etc.

Pull requests welcome!
