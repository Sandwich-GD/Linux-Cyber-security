
## Advanced Options & Notes

**Minimal/Source-Based Distros**  
For maximum control and learning:  
- *Linux From Scratch (LFS)*: Build your own system from the ground up.  
- *Gentoo*: Compile everything with custom USE flags for minimal attack surface.  
- *Alpine Linux*: Lightweight, musl-based, great for containers and minimal setups.  
- *\*BSD (FreeBSD, OpenBSD, NetBSD)**: Not Linux, but excellent for security-focused learning (OpenBSD's secure by default philosophy is legendary).

**Hardened Kernels**
- **CachyOS Kernel**: Includes BORE scheduler, LTO, and exploit mitigations.  
- **TKG Kernels**: Custom patches for performance + latency improvements (great for desktop + security balance).

**Mobile Privacy**  
- *GrapheneOS* (Pixel only) or *CalyxOS*: De-Googled, hardened Android ROMs with sandboxing and verified boot.

**Tor Beyond the Browser**  

The Tor *network* can route all your traffic:  

**Use torsocks to wrap commands**

```torsocks curl https://check.torproject.org```

**Or use proxychains for broader app support**

```proxychains firefox```

## Real Scenarios
Do not use the same password everywhere, because hackers move FAST.

They will try the password on Email, Games, Google, etc. etc.

When you see a shady email, like someone from microsoft or discord offering something for free?

Its too good to be true.

When you see someone message you on discord, asking for something really specific?

Like they ask you to go on a webpage, get a bookmark, go on your games website, and click it?
Dont.


## Common sense (things not to do)

**Dont click consent when a website asks for "your data".**

Dont accept anything that seems too good to be true.

Dont go "ooohhh ill harden this part of firefox later", do it right then and there.

**Dont ever show your camera to strangers.** **And if you do, turn it off ASAP.**
**Heck, its better if you just take the USB plug out.**

Dont forget to check for any security leaks.

**AND THE MOST IMPORTANT ONE: DONT USE GOOGLE!**

Thats it!
