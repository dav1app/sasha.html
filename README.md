# sasha.html
The nicest way to encrypt some "very important images" ( ͡° ͜ʖ ͡°). Fast and safe like a handjob.

![alt text](https://github.com/davimello28/sasha.html/blob/master/printscreen.png)

## What is it?
It is a small auto-replicant HTML file that encrypts a file and creates another HTML file with the encrypted file inside. Each HTML can encrypt another files, so you don't need to install or access anything. You only need a browser. 

## Why?
I believe that encryption should be available to everybody. I wrote this on HTML + CSS + JS purely because I believe this is the easiest way to make everybody understand what is going on.

## Why this is cool?
Because you don't need to install anything but the browser. Every browser that supports the Web.crypto functions can decrypt the files (Safari still doesn't have this). Also, some files can be opened directly into the browser, without the need to download it.

## How to use it?
Just open `sasha.html` and type a password, than select a file **(on that order)**. After that, the download prompt should open. 

Try opening the HTML file that we downloaded and you are going to see 2 different boxes. One is for new encription files, the other is your file. Type your password and check your file. 

## What do we need to improve?
- Basically everything. I coded it in only one night. I am not 100% satisfied with the code.
- The files are getting twice their size due to HEX saving. We should change it to encode it better. The ideal size is filesize + sasha.html minified.
- There is no error when we type the wrong password.
- It is not minified yet (6kb). It should be, but we need to be a little careful because the file is auto-replicant. 
- We need to check if the files opened in the browser are stored somewhere on the computer. Understanding how the browser works with this files is desirable.
- I am not sure if the AES-GCM with SHA-256 is secure enought and this files are sensible to brute force attacks.
- Encripting multiple files is a pain in the arrrs.
- We should have a better testing for browser compatibility.
- Optimizing buf2hex and hex2buf functions.

## Is that a filesize limit?
So, nice question. My research results are inconsistent. I am pretty sure that files arround 50mb can be encripted and decripted just fine in Chrome, Firefox and Opera (updated ones). It depends on the browser.

## How you can help? 
- Please use the Issues.
- Feel free to make pull requests.

## License
- I am not responsable for any damage of the file. I use this for myself, and it has worked like a charm.
- Also, I am not responsable for your browser. 
- If you are going to use this as a corporate solution, be aware that I do not recommend this! Seriously, don't do that.
- Don't sell it to anyone. This thing is free and it is important to keep it that way.
- Be kind to others.
