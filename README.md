# Miyuki-Ransomware

My first ransomware program written in C++—no graphical user interface, simple, lightweight, and optimized. I discovered that this is the magic of switching from Python to C++—not only the cross-Windows compatibility (support from XP to 11), but also how lightweight and optimized it is. Crypto++ was used for cryptographic algorithms (AES-256, RSA-2048, and SHA-256), and I’ve tried to protect the key against swapping as much as possible using VirtualLock and system reboots. I’m creating this ransomware in Miyuki's name, as a projection of myself. 

I plan to update it with new features such as leaving a random message in the encrypted file, encrypting the MBR with the same key, blocking more system tools, detecting which processes have been used, self-replicating, and better camouflaging itself. I might even try adding graphical windows to make it look nicer; I’ll do my best to improve it.

For now, this is either the first or the last version—it depends on how well I do.

https://github.com/user-attachments/assets/2e0ec782-946b-4222-b857-0d5a4c320dea

(I couldn't convert it to a GIF because of the 10 MB limit, greetings to all!)
