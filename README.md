# paperlist
The paper on security I've read since 2018

## 2018
### March
[Key Reinstallation Attacks: Forcing Nonce Reuse in WPA2](https://papers.mathyvanhoef.com/ccs2017.pdf): [[Demon](https://www.youtube.com/watch?v=Oh4WURZoR98)]
```
Key reinstallation attack to change the connection parameter.Packet replay,decrypt and forge is possible.
More specifically,in the 4-way handshake, every time message 3 is received, the session key is reinstalled.
So we can attack by replay message 3.(Worth trying)
```

[CFIXX: Object Type Integrity for C++](http://wp.internetsociety.org/ndss/wp-content/uploads/sites/25/2018/02/ndss2018_05A-2_Burow_paper.pdf): [[Implementation](https://github.com/HexHive/CFIXX)]
```
Nowadays C++ has ControlFlow Integrity (CFI) to prevent that the vatable from being corrupted. But attacker 
can corrupt the type information of an object to make it wrongly dispatched. If the set of function determined 
by CFI is large enough, attack can find useful gadget. So this paper presents a Object Type Integrity (OTI) 
mechanism to address this problem with little overhead.
```
