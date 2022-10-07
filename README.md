<!--
A little tutorial on markdown. It's kind of like HTML. For example, it uses
  the same comment deliminators.
-->

<!-- Just like HTML, it works for one line or multiple. -->

<!-- 
From here down is a header. Note that has before the sentence -- that means it's
  the biggest header, Header 1, or H1. One has is essentially like <h1></h1>. 
  Two hashes is H2, one step smaller, on down to Header 6.

This is a great super quick tutorial on markdown:
https://www.markdowntutorial.com
-->


### Your directory structure should look like this:  

```bash
(this directory, tagel-legato)  
├── Data  
├── Instruments  
│   ├── Tagel Legato.nki  
│   └── (etc)  
├── KSP  
│   ├── main.ksp  
│   └── (etc)  
├── README.md  
├── Resources  
│   ├── data  
│   ├── ir_samples  
│   ├── performance_view  
│   │   └── tagel-legato.nckp  
│   ├── pictures  
│   │   └── Jouhikko Tiny.png  
│   └── scripts  
│       └── main.txt  
├── Resources.nkc  
├── Resources.nkr  
└── Samples -> [your samples folder]  
 ``` 

**Samples are not being pushed to this repo.** Be sure to create a symbolic link pointing to wherever they live on your machine, and be sure to name the link Samples, as shown above.  
**Resources/pictures also is not being pushed to this repo.** Make sure to manually add or symlink to any picture files.  
