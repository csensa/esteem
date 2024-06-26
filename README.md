# esteem

A neat Bash script to build/install/update the Enlightenment ecosystem on Ubuntu 23.10.

Please take a look at the comments in the script before running it.

> [!NOTE]
> It may be useful to keep a record of the pre-existing system status, before proceeding with the installation.
>
> Check out our [backup script](https://gist.github.com/batden/993b5ee997b3df2c3b075907a1dff116).

## Get started

Before using esteem, you will need to install the git and sound-icons packages on your system.

Open a terminal window and type in the following:

```bash
sudo apt install git sound-icons
```

Next, clone this repository:

```bash
git clone https://github.com/batden/esteem.git .esteem
```

This creates a new hidden folder named .esteem in your home directory.

Copy the esteem.sh file from the new .esteem folder to your download folder.

Navigate to the download folder and make the script executable:

```bash
chmod +x esteem.sh
```

Then execute the script with:

```bash
./esteem.sh
```

To run it again later, open a terminal and simply type:

```bash
esteem.sh
```

> [!TIP]
> Use auto-completion: Type _est_ and press the Tab key.

That's it.

You can uninstall Enlightenment and related applications from your computer at any time.

See [meetse.sh](https://github.com/batden/meetse).

## Update local repo

It is good practice to check for updates to the local repository before using the script.

To do so, change to ~/.elluminate/ and run:

```bash
git pull
```

## In the picture

![GitHub Image](/images/enlightened_desktop.jpg)
