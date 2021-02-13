<p align="center">
   <img src="https://github.com/Bhupesh-V/dotman/blob/master/assets/dotman-logo.png?raw=true" height="230">
</p>



<samp>
  <h3 align="center">
    <a href="https://www.freecodecamp.org/news/build-your-own-dotfiles-manager-from-scratch/">✨ Learn how I made d○tman from scratch ✨</a>
  </h3>
</samp>


## Demo 🔥

<p align="center">
  <img alt="dotman-demo" src="https://user-images.githubusercontent.com/34342551/97109739-ee43fc00-16fa-11eb-8ed2-3a69ad7073b3.gif">
</p>


## 🌠 Features

* **Single file manager** (Portable)
* **No config files for dotman** (No `.dotrc` 🤦)
* **No useless arguments** (single command 😎)
* **Easy to use**
* **Extendable ⚒**, _Available as a Template_
* **Fewer Dependencies**
  - **`Git`**
  - **`Bash>=3`**


## Wait! it's not written in a fancy language

And it doesn't have to be. Why?

- Your focus should be on your **dot files & scripts** rather than on a dotfiles manager or how to use it.(_Wait I forgot what was the command to push files? Is it `dt push` or `dt --push`_)
- Creating a overly-complex solution for something simple should not be the goal.


## 💠 Installation

### via `curl` ➰

```shell
sh -c "$(curl -fsSL https://raw.githubusercontent.com/Bhupesh-v/dotman/master/tools/install.sh)"
```

### via `wget` 📥

```shell
sh -c "$(wget -O- https://raw.githubusercontent.com/Bhupesh-v/dotman/master/tools/install.sh)"
```

### via `httpie` 🥧

```shell
sh -c "$(http --download https://raw.githubusercontent.com/Bhupesh-v/dotman/master/tools/install.sh)"
```

> **dotman** is installed by default in `/home/username/dotman`, your `$HOME` directory.


Now run **`dotman`** for 1st time set-up.

1. Enter repository URL (without `.git`).
2. Specify folder you want to clone the dotfile repo to (relative to `/home/username/`).
3. Open up new terminal 🚀.

### Manually (you ok ?)

1. Just grab **dotman.sh** from [Releases 🔼](https://github.com/Bhupesh-V/dotman/releases) and store it anywhere on your system.
2. Change file permissions to be 🏃 executable.
  ```bash
  chmod +x dotman.sh
  ```
3. Set alias for dotman _(optional)_. Alternatively modify your `.bash_aliases` file. 
  ```bash
  alias $(pwd)/dotman.sh=dotman
  ```
4. Run **dotman**.
  ```bash
  dotman.sh
  ```

## Usage

Just run **`dotman`** anywhere in your terminal 🖖.

```bash
dotman
```
Leave the rest to it.


## What else 👀

dotman exports 2 variables in your default shell config (`bashrc`, `zshrc` etc):

1. `DOT_DEST`: used for finding the location of dotfiles repository in your local system.
2. `DOT_REPO`: the url to the remote dotfile repo.

You can change these manually if any one of the info changes.



<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->
<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!
