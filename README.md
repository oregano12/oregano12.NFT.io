# Frontend Mentor - NFT Preview Card solution

This is a solution to the [NFT Preview Card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Overview
### Screenshot
![image](https://github.com/oregano12/oregano12.NFT.io/blob/main/screenshot.png)

### Links
- Solution URL: https://github.com/oregano12/oregano12.NFT.io/blob/main/index.html
- Live Site URL: https://oregano12.github.io/oregano12.NFT.io/

## My process
### Built with
- Visual Code Studio
- CSS custom properties
- Flexbox

### What I learned
I learned how to apply basic hover functions. I'm happy with how the hover turned out on the main image.

```css
  .image {
    position: relative;
  }
  
  .mainImg {
    width: 100%;
    height: 100%;
    height: auto;
    border-radius: 10px;
  }
  
  .image div {
    position: absolute;
    background-color: hsl(178, 100%, 50%, 60%);
    top: 0;
    width: 100%;
    height: 100%;
    opacity: 0;
  }
  
  .image div:hover {
    opacity: 1;
    cursor: pointer;
    border-radius: 10px;
  }
  
  .image div img {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
  }
  
  .image .mainImg:hover + .hover-active {
    display: block;
  }
```

### Continued development
I wanna keep improving my hover knowledge. I still feel like I have much to learn in this regard.

## Author
Oregano12
