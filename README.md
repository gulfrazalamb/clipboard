# Clipboard!
"Hey everyone, today I wanted to share a tool that I recently created using Bash. It's a clipboard tool that allows you to quickly copy and paste text from your terminal without having to use your mouse or trackpad.

The tool works by using the xclip command, which is a command-line tool for working with the X clipboard. It allows you to read and write data to and from the clipboard, which makes it a powerful tool for working with text in the terminal.

To use the tool, you simply need to select the text you want to copy in your terminal, and then run the clipboard command. This will copy the selected text to the clipboard, which you can then paste using the paste command(ctrl+shift+v/ctrl+v).

The tool also has a clear command, which allows you to clear the contents of the clipboard. This can be useful if you want to ensure that sensitive information is not left in the clipboard after you're done working with it.

Overall, I think this tool is a great addition to my workflow, as it allows me to quickly and easily work with text in the terminal without having to switch back and forth between my mouse and keyboard. If you're a fan of working in the terminal, I definitely recommend giving this tool a try!"

# Installation guide!

sudo apt install xclip

git clone https://github.com/gulfrazalamb/clipboard.git

cd clipboard/

sudo chmod +x clipboard

sudo mv clipboard /usr/bin/

*that's it!

# Usage!

cat filename | clipboard

*you get your texts in clipboard*

# Example:-

cat test.json | clipboard

or

cat you_file_name.txt | clipboard

or

cat your_file_any.format | clipboard

