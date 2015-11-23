# Switch To Vim For Good

This guide is coming from an email I used to send to newcomers to Vim. It is not intended to be a complete guide, it is about how I switched myself.

My decision to switch to Vim has been made a long time ago. Coming from TextMate 1, I wanted to learn an editor that is Open Source (so I don’t lose my time learning a tool that can be killed), cross platform (so I can use it everywhere), and powerful enough (so I won’t regret TextMate). For these reasons, Vim has always been the editor I wanted to learn, but it took me several years before I did it in a way that works for me. I tried to switch progressively, using the [Janus](https://github.com/davelab6/janus) Vim distribution for a few months, then got back to using TextMate 2 for a time, waiting for the next attempt… here is what finally worked for me.

Original gist with comments: https://gist.github.com/bpierre/0a0025d348b6001394e0

## Non Optional

1. Watch the Derek Wyatt videos in order (at least the “Novice” ones for now): http://derekwyatt.org/vim/tutorials/
2. Read the first part of this Stack Overflow answer: http://stackoverflow.com/questions/1218390/what-is-your-most-productive-shortcut-with-vim/1220118#1220118
3. Read “The Problem with Vim”, just to warn you: http://haldean.org/vim-problems/
4. Launch vimtutor and finish it. Start playing with your new editor.
5. Read “How to Switch to Vim” by David Bryant Copeland (entirely): http://naildrivin5.com/blog/2013/04/24/how-to-switch-to-vim.html
6. Read “Coming Home with Vim” by Steve Losh (entirely): http://stevelosh.com/blog/2010/09/coming-home-to-vim/

## My Advices

- Start with an empty .vimrc, no plugins, no Vim distribution (like Janus). Only add what you understand, do not add too much things at once. Read other people .vimrc files. Vim is about “building”, or configuring, your own editor.
- Do NOT stay in edit mode! The “normal” mode is called like that for a reason: you should stay in that mode most of the time. Switch to insert mode, insert something, then go back to normal mode.
- Put your .vimrc on a repository hosting service (Gitlab, Bitbucket, GitHub…) so you can easily use it from everywhere and share it with others.
- Create your own commands everytime you see yourself doing the same thing again and again, especially when entering in command line mode (by pressing `:`). Start by mapping :w<enter> to something faster to type. For me it’s `,s`, because `,` is my `<Leader>` key, and `s` is always under my opposite hand.
- Vim is a game which is incredibly rewarding after the first learning phases. You will learn to speak to your editor using a language. Every time you will learn a new noun, you will be able to use it with any verb or adjective that you already know. That is why with the time, every small thing you learn will be more and more powerful.
- Try to learn new tricks from time to time, and remember to practice them so your brain can assimilate them and use them without even thinking about it.
- Forget about your arrow keys. If you use them, your brain will never develop any good moving habit. Try to not use hjkl too much. kkkkkllllllllll is not faster than using a mouse: if you repeat the same key more than 3 times, there should be a way to move faster. Find it and use it.
- If you more or less plan to buy a new keyboard, do it. This keyboard is now your Vim keyboard, and that could help you to create a mental switch.
- You won’t be as productive as with your previous editor until one or two weeks, depending on what you do. Commit. Don’t look back. Your brain will hate it, but don’t listen to him, he will quickly find a way to be productive again.

## Other Things

- I use Vim in my terminal because I am using [Tmux](http://tmux.github.io/), but a graphical Vim is not “inferior” in any way, feel free to use what you feel will work best for you. MacVim is a good one on OS X, and gVim on Linux / Windows.
- Vimcasts: http://vimcasts.org/
- Base16 is a nice theme: http://chriskempson.github.io/base16/
- _usevim_ is a cool newsletter, subscribe: http://usevim.com/
- The Vim subreddit: https://www.reddit.com/r/vim/
- Vim Golf can help to discover new tricks: http://www.vimgolf.com/
- Vim after 11 years: http://statico.github.io/vim.html
- A Good Vimrc: http://dougblack.io/words/a-good-vimrc.html
- Learn Vim Progressively, useful list of commands: http://yannesposito.com/Scratch/en/blog/Learn-Vim-Progressively/
- I am personally using NeoVim, a Vim fork: http://neovim.org/
- My ugly .vimrc <3 https://github.com/bpierre/dotfiles/blob/master/vimrc

Another approach that seem to work for some people is to take the opposite way: slowly learning Vim by using it as a “normal editor” to start. It didn’t work for me, but maybe it could work for you: http://yehudakatz.com/2010/07/29/everyone-who-tried-to-convince-me-to-use-vim-was-wrong/
