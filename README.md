# PWST Resources

This repository contains resources for students taking the TCM Academy course "Practical Webapp Security and Testing." 

## Usage

Code in the repo is used for lab setup and for specific lab exercises. It should be cloned onto both the Kali VM and the Ubuntu VM.

To download this repo, in a Terminal, run:

```bash
cd ~/Downloads
git clone https://github.com/mttaggart/pwst-resources
```

You'll now have the `pwst-resources` folder in your `Downloads` folder.

## Kali Setup

To run the setup script, Run the following in a Terminal:

```bash
cd ~/Downloads/pwst-resources/kali-setup
chmod +x ./setup.sh
./setup.sh
```

There will be a few points where you need to provide input to the script, but otherwise it should run smoothly. If you wish to use the optional fish shell that is configured, make sure you run the `chsh` command as listed at the end of the install script!
