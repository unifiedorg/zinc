![Unified Banner](https://raw.githubusercontent.com/unifiedorg/.github/main/img/logo-banner.png)
# Zinc (Scripting language)
Zinc is a quick, simple and easy to use scripting language written in C++ with an extremly simple syntax.
You have to write minimal code, to achive the speed of compiled languages. That's right, its fast too!
Minimal, easy to use and fast. Read below for more information!

# Installation
## Generic

1. Download the appropriate version of zinc.
2. Rename file to `zinc`.
3. Add the zinc executable to a folder that is in PATH.
4. You can now run zinc scripts by running `zinc /path/to/script.zn`.

Below are the intructions on how to install as well as setup zinc, targetted at specific operating systems.

## Linux

1. Download `zinc-linux-1.0.0`.
2. Add `~/bin` to PATH by adding `export PATH="/home/$USER/bin:$PATH"` to the end of your `.bashrc` file present in the home directory.
3. Rename `zinc-linux-1.0.0` to `zinc` by running `mv zinc-linux-1.0.0 zinc`.
4. Move your `zinc` executable to the `~/bin` path.
5. You can now run zinc scripts by running `zinc /path/to/script.zn`.

## Windows

1. Download `zinc-win[system-arch]-1.0.0.exe` (Rename `[system-arch]` to the architecture of your system).
2. Rename the file `zinc-win[system-arch]-1.0.0.exe` to` zinc` (Rename `[system-arch]` to the architecture of your system).
3. Make a folder, and add it to PATH ([How to add folder to PATH](https://linuxhint.com/add-directory-to-path-environment-variables-windows/)).
4. Move your zinc executable to the folder you added to PATH.
5. You can now run zinc scripts by running `zinc /path/to/script.zn`

# Documentation
More in-depth documentation is coming soon, however till then, here is a simeple hello world script!

1. Create a file, `hello.zn`
2. Edit that file to include the following `print` statement :
   ```
   print: "Hello World!"
   ```
3. Run the script by running the following command `zinc hello.zn`, and boom, you now have a Hello World script!
   No annoying-to-write boilerplate code which is which is messy and hard to read (java), just a simple `print:`
   statement!
