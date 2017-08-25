# git-yolo
YOLO Mode for GIT

## What is YOLO Mode?

People always say that you should commit often.

Well sometimes you can't even bother to decide what and when to add files and, even worse, keep writing convoluted commit messages.
So with YOLO mode you will automatically force push every change. ¯\\\_(ツ)_/¯

```
Everything?
```

That's right! Everything. If you press save it will be force pushed to origin.
With a very nice commit message that includes a pretty emoji 😉. (Because it's 2017, it needs emojis)

Git YOLO was even developed using itself!!!! Say wuuuuut?!?!?!

## Usage

Easy!

Simply install it through npm:

```bash
npm install git-yolo -g
```

And start the mode with:

```bash
git-yolo
```

Or even add an alias:

```bash
git config --global alias.yolo git-yolo
git yolo
```

Your changes might have introduced breaking changes, but you got more important things to worry about in your short time on Earth, so you can make sure to bump the major version on every save with the `--carpe-diem` flag:

```bash
git-yolo --carpe-diem
```

## But Y DOE?

Well simple.
Sometimes during hot patching you need to push everything very fast.
You don't have time to save it, test it, run it, add it, commit it and push it.
Just press Save!

## What's Next?

This should probably be slightly more customizable.
- For instance if you have a CI perhaps you should be able to include a `[ci-skip]` in the commit message.

