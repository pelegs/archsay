ASCII art for the arch logo to be used in conjuction with cowsay and maybe even lolcat.

For example, the following command produces the arch logo saying a random fortune quote and colored randomly by lolcat:
`$ archsay="fortune | cowsay -n -f arch | lolcat -h $(( rand48(seed) )) -v $(( rand48(seed) ))"`
The file `arch.cow` should be in `/usr/share/cowsay/cows` for all users to have access to it.

In addition, a tapir ASCII art is provided in the file `tapir.cow`.
