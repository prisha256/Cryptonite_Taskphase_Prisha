3. **Pondering Paths (Root Directory)**  
   Ran the `pwn` program from the root directory and got the flag.  
   `pwn.college{k3F4cuvtrGOENJUpnp3NhO-4FdP.dhzN5QDLycDO0czW}`

4. **Pondering Paths (Challenge Directory - Absolute Path)**  
   Found the program under `/challenge/run` and executed it—easy flag!  
   `pwn.college{AgIsmjTjgbjGlPZBj1OdIcuwGFk.dVDN1QDLycDO0czW}`

5. **Pondering Paths (Sys Directory)**  
   Switched to the `sys` directory, ran the command, and got the flag.  
   `pwn.college{wb4GXAT6lfXD-_hNYtFJr8qTB7T.dZDN1QDLycDO0czW}`

6. **Pondering Paths (Zoneinfo Directory)**  
   Navigated to `/usr/share/zoneinfo/posix/Asia` and found the flag there.  
   `pwn.college{wb4GXAT6lfXD-_hNYtFJr8qTB7T.dZDN1QDLycDO0czW}`

7. **Pondering Paths (Relative Path)**  
   Used the relative path `challenge/run`—worked perfectly!  
   `pwn.college{Md6POpXmNfQ5EZiBDmwHBH7a7mg.dlDN1QDLycDO0czW}`

8. **Pondering Paths (Relative Path with Dot)**  
   Used `./challenge/run` and it gave me the flag.  
   `pwn.college{ksLNJtl_-Yd-HjO22LLwRbq-oVJ.dBTN1QDLycDO0czW}`

9. **Pondering Paths (Challenge Directory Run)**  
   Learned that running just `./run` also works—got the flag!  
   `pwn.college{MfojA_cfZ7JZsW3XBpKyL6mQduM.dFTN1QDLycDO0czW}`

10. **Pondering Paths (File Argument)**  
    Passed a file as an argument to `/challenge/run` and received the flag.  
    `pwn.college{4yFedHzA3yTe4IekXfus88tkJwj.dNzM4QDLycDO0czW}`
