# To-do

### Week of Monday, January 09, 2023

##### Cote: 
- Install Sublime Text and SublimeKSP.
- Clean up new instrument's variable naming scheme (make it consistent).
- Change comment scheme from KSP-native `{}` to SublimeKSP `//`

##### Hartov:

##### Ruger:

### Next meeting (Tuesday, January 17, 2023)
- Ruger and Cote refactor Cote's code using macros.

### Instrument general to-do:
- Allow user to change CC for sliders.
- Show waveform of current sample.
- Neighbor zone round robin (i.e. take another sample and pitch it down/up)
- UI option for round robin or not
- New github repo? Just call it bass-tagelharpa and have different articultions within it.

### AJA general to-do:

##### Ruger:
- Check out Koala KSP.
- Implement re-bowing control.
- Look over SNS KSP library, potentially make for AJA.

### Inspiration
- Westwood Instruments: Look at how you can "lock" a group (they call them "improv a," "improv b")

# How to set up this repo locally

<!--
First, a little tutorial on markdown. It's kind of like HTML. For example, it 
usesthe same comment deliminators.
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
1. Install WSL2 on your PC:
   https://learn.microsoft.com/en-us/windows/wsl/install
2. Install Windows Terminal:
   (just search for it in the Microsoft Store).
3. 
4. Install git: sudo apt install build-essential
5. Make a development directory inside of the AJA directory on your computer.
6. Run git clone repo-url and it'll clone to that folder.
