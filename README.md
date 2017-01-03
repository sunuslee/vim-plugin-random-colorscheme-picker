## ABOUT ##

Power VIM Users like us have already wasted tons of time to choose our favorite colorschemes, and may still not be satisfied with the current colorschemes. So I wrote this plugin to help us out, to meet the perfect colorscheme that we are __DESTINED__ to be with. (just like your lovely partners:)

Written by sunus Lee

sunus.the.dev[at]gmail.com

Wed Dec 12 11:50:55 CST 2012

Added Windows Support, great news for windows vim users, right? :)

### Installation ###

### As a Pathogen bundle ###
If you have pathogen installed and can just copy into ~/.vim/bundle like this:

cd ~/.vim/bundle && \
git clone https://github.com/sunuslee/vim-plugin-random-colorscheme-picker

if you are using Janus:

cd ~/.janus && \
git clone https://github.com/sunuslee/vim-plugin-random-colorscheme-picker


### Without Pathogen ###
Just copy randomColorPicker.vim to your VIM runtime plugin path:


##### Linux #####

You may need to create ~/.vim/plugin directory if it doesn't exist:

`mkdir -p ~/.vim/plugin`

then:

`cp plugin/randomColorPicker.vim ~/.vim/plugin`

##### Windows #####

1. create a directory at:

 `C:\Users\YourUsername\vimfiles\plugin`

 or enter directory:

 `C:\Program Files\vim\vim73\plugin`

 vim73 might be vim72 or whatever.. as long as it's where your vim is installed, it's valid.

2. copy plugin/randomColorPicker.vim to that directory.

### Usage ###
You will need to add the following line to your .vimrc file to pick the
next random colorscheme:

CSNext


* __ALL The Commands below are CaseSensitive__

* if you  __LOVE__  this colorscheme,

  Enter( In Normal Mode )

  `:Love`

  then I will never change your colorscheme again.

* if you __HATE__ this colorscheme and don't want to see her again,

  Enter( In Normal Mode )

  `:Hate`

  then I will never pick this colorscheme for you and then

  randomly pick a new colorscheme.

* if you somehow regret what you did and want to get the hated colorscheme back,

  Enter(In  Normal Mode)

  `:Back`

  then all you hated colorscheme will back to select pool, and you might see

  her again:)

* Enter(In Normal Mode)

  `:CS`

  to see current colorscheme

* Enter(In Normal Mode)

  `:CSnext`

  to switch to a new random theme without restarting vim.

#### Variables ####
* *g:colorscheme_user_path*

  Set to a comma-delimited string for Vim to look for colorschemes in additional areas, e.g.

  ```
  let g:colorscheme_user_path = '~/.vim/bundle/vim-colorschemes/colors'
  ```

  **NOTE:** This only works if Vim is aware of the other colorscheme paths, such as when you install colorscheme repositories using a plugin manager.

### Tips ###
  Use this plugin with a large colorsheme pool will increase the possibility of meeting the right ColorScheme for you.

  So, I recommand you also use the ColorScheme Pack at:

  [Colo(u)r Sampler Pack : Oct 2012 Update](http://www.vim.org/scripts/script.php?script_id=625)

  Big Thanks to __Robert Melton__ for his awesome work!

  A more complete and actively maintained package can be found [here](https://github.com/flazz/vim-colorschemes).

### Any Feedback and Suggestions is welcomed ###
  mail me: sunus.the.dev[at]gmail.com
