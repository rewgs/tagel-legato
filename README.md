<!--
A little tutorial on markdown. It's kind of like HTML. For example, it uses
  the same comment deliminators.
-->

<!-- Just like HTML, it works for one line or multiple. -->

<!-- 
From here down is a header. Note the three hashes before the sentence -- that 
means it's the third biggest header, Header 3, or H3, or in HTML, <h3></h3>. 
One hash is H1, the biggest, and six hashes is H6, the smallest.

This is a great super quick tutorial on markdown:
https://www.markdowntutorial.com
-->


### Your directory structure should look like this:  

```bash
(this repo, tagel-legato)  
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
