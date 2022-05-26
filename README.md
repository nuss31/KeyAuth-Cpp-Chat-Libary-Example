# KeyAuthCpp-Chat-Libary-Example
KeyAuth CPP Example with Library that has the Keyauth Chat/Channel Function included and a bug fix

I made this cause i didn't want to wait for the KeyAuth devs to include the Chat function so i made it by myself and now i share this to anyone
who needs it.

This example lets you send messages to the Keyauth Chat function and Read all Messages and the Author and the Timestamp of the Messages.
I also fixed a bug that Keyauth Devs didn't think of.
The bug simply was the cin function cause when a user had a Space in his Name or Password the cin function could not Read it
cause the cin function only takes characters till the Space and i fixed it with this:
std::getline(std::cin, string);

Credits to [KeyAuth](https://github.com/KeyAuth)
