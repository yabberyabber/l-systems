# l-systems

I thought it was pretty and I got bored waiting for code to compile one day.  For more info on l-systems, check out https://en.wikipedia.org/wiki/L-system and http://algorithmicbotany.org/papers/abop/abop.pdf.

Rules in the "Rules" section must be specified as a valid JSON dict with the character being replaced as the key and the pattern to replace it with as the value.  '[' pushes the current cursor position/orientation onto the stack.  ']' pops the latest off the stack.  This is how branches are made easily.

https://yabberyabber.github.io/l-systems/
