Names: Nimai Kasibatla 


## Check Your Understanding

### 1) Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.

- [x] Within a GitHub action that runs whenever code is pushed  
- [ ] Manually run them locally before pushing code  
- [ ] Run them all after all development is completed

**Explanation**:
I would fit my automated tests in my recipe project development pipeline within a GitHUb action that runs whenever code is pushed. I would do this because running tests automatically through GitHub Actions everytime you push helps catch bugs early on before they are even merged into the main branch. This is really important to preserve the quality of the main branch. This also makes sure that every single change being made is checked and validated through automated tests, which largely reduces the chances of broken features being merged into the main branch. 

### 2) Would you use an end-to-end test to check if a function is returning the correct output?

**Answer**: No

### 3) What is the difference between navigation and snapshot mode?

**Navigation Mode:** analyzes a webpage right after it loads which captures a full performance audit that records load time, interactivity, and shifts in layout. It actually simulates an actual human user visiting the site from when it is first opened. 

**Snapshot Mode:** captures the current visual and DOM state of the webpage without including any sort of interaction. It is very useful for determining accessibility issues and static forms of content. It does not measure any sort of performance metrics like speed to load or interactivity. 

### 4) Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results.

1. **Add a `<meta name="viewport">` tag** 
- This is missing from the site, which hurts mobile responsiveness
2. **Properly size and optimize images**
- The audit shows potential savings of over 500 KiB by resizing and compressing images.
3. **Reduce unused JavaScript and CSS**
- Lighthouse detected large amounts of unused code. 





