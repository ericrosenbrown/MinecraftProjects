## Minecart XOR Calculator

![Front view](./front.jpg "Front view")
![Top view](./top2.jpg "Top view")
![Inside view](./in.jpg "Inside view")

https://www.planetminecraft.com/project/minecart-xor/

I made a new way to use mine-carts to make logic gates. This specific logic gate of minecarts is the XOR gate.

In my previous project, I only used OR and ANE gates to make my calculator work. I devised a way so now I can use mine-carts for my XOR gates. The basic idea is that when one input is on, it powers one cart and it goes down the hill and lights the output. But when two are on, the power cancels out, and it does not go down the hill at all.

When I first made this, the firs two minecarts near the input were for it, but later on I realized they weren't needed. All they do is help keep straight input. Anyways, what I set up were two slopes with a minecart on each one. On each slope the minecart starts on a non-powered rail then the next part of the slope is a normal rail, then the next part is a powered rail. The left slope is for the left input and the right cart is the right input. The already powered power-rails are controled by the opposite input inverted, so when the right input turns on, the rail turns off, and vise versa. So the idea is if I turn on the left input, the left rail's first powerrail will turn on, and it will go down to the next powerrail, which will be on because it's inverted, and it will send the minecart down, hit a detector rail, and send the signal. This works the same for the right one. But, if both are one, they both go down the slope, but since the signals control the second inverter, the second powerrails turn off, catching both minecarts, so there will be no signal. Hope that makes sense.
