Open the file `/etc/initscripts/anki-audio-init` using nano and scroll to the bottom till you see an option `amixer cset numid=33 74` and change `74` to a lower value but **DO NOT go above 80 or speaker damage may occur**.

Once the changes are done you can either reboot or just run `amixer cset numid=33 ##"` "##" being your changed value
