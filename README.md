# Text Editor

## Table of Contents

* [Description](#description)
* [Code Examples](#code-examples)
* [Important links](#important-links)
* [Languages Used](#languages-used)
* [Questions](#questions)

## Description

The purpose of this project was to edit a given set of code in order to produce a working text editing application that runs in the browser.


## Code Examples
Example of Code 

```js
export const putDb = async (content) => {
  const db = await openDB('jate', 1);
  const transaction = db.transaction('jate', 'readwrite');
  const obStore = transaction.objectStore('jate');
  const request = store.add({jate: content}); 
  const result = await request;

  console.log("successfully saved to databse", result);
};
```
Example of Code 

```js
   butInstall.addEventListener('click', async () => {
    const event = window.deferredPrompt;
    if (event) {
        event.prompt();
        window.deferredPrompt = null;
        butInstall.classList.toggle('hidden', true);
    
```

## Important Links
[GitHub Repository](https://github.com/keekerr/Text-Editor)

[Deployed Application]()

## Languages Used

![JavaScript Badge](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQI-yru0g__m2utbuabzKfGBlNLIe2ahblJbg&usqp=CAU&w=100&h=120)
## Questions

If you have any questions regarding this project, please feel free to contact me at this email: keeley.s.sprouse@gmail.com

Other examples of projects I have worked on can be viewed on Github via this link: [keekerr](https://github.com/keekerr)
