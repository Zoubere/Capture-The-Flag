# Serpentine CTF Write Up

    Y
  .-^-.
 /     \      .- ~ ~ -.
()     ()    /   _ _   `.                     _ _ _
 \_   _/    /  /     \   \                . ~  _ _  ~ .
   | |     /  /       \   \             .' .~       ~-. `.
   | |    /  /         )   )           /  /             `.`.
   \ \_ _/  /         /   /           /  /                `'
    \_ _ _.'         /   /           (  (
                    /   /             \  \
                   /   /               \  \
                  /   /                 )  )
                 (   (                 /  /
                  `.  `.             .'  /
                    `.   ~ - - - - ~   .'
                       ~ . _ _ _ _ . ~

Welcome to the serpentine encourager!


a) Print encouragement
b) Print flag
c) Quit

What would you like to do? (a/b/c) 

The cli program gives three options to input, however the option for printing the flag b) does not output the flag. When we go into the program,
we can see the print_flag() function is not called anywhere in the program. Putting the function under the b) promt will allow us to execute the 
function from the cli, and output the flag. 

picoCTF{7h3_r04d_l355_7r4v3l3d_8e47d128}
