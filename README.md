How to install.

You'll need a terminal, for this:

First, make sure Skype 5 can accept alternative styles, by typing this command in:

    defaults write com.skype.skype SKChatStyleVariants YES

Then, add make the directory structure you need to put custom styles where Skype looks for them:

    mkdir -p ~/Library/Application\ Support/Skype/ChatStyles/


Then cd to it:

    cd ~/Library/Application\ Support/Skype/ChatStyles/

then clone this badboy into that directory:

    git clone https://github.com/mrchrisadams/Comic-Sans.SkypeChatStyle.git

Restart Skype, then choose it from `Preferences -> Messaging`.

BOOM! See how long you can last before you claw out your own eyes!

