Boot into single user mode (CMD + S)

sudo nvram 000fa4ce-b62f-4c99-9cc3-6815686e30f9:gpu-power-prefs=%01%00%00%00

reboot

Boot into recovery (CMD + R)

Open terminal (Utilities > Terminal)

cd /

cd System/Library/Extensions

rm -r GeF*

reboot

PROFIT


//sudo nvram fa4ce28d-b62f-4c99-9cc3-6815686e30f9:gpu-power-prefs=%01%00%00%00

https://apple.stackexchange.com/questions/166876/macbook-pro-how-to-disable-discrete-gpu-permanently-from-efi
