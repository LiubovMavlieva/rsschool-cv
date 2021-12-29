# Liubov Mavlieva
*********
## Contact information:
email: mavlieva13@gmail.com
discord: Liubov(@LibovMavlieva) 

The desire to learn something new in life is my main motivation to wake up in the morning. In the middle of 2021, I got carried away with programming and since then I have been studing for 7 months at Yandex Practicum (front-end developer), as well as in the process of studying at rs school.
I strive to develop in front-end development and my goal for 2022 is to find a job in the IT field.
*********
## At this stage, I have the following skills:
*  I can make up Figma layout projects using the BEM methodology.
*  I can create adaptive layout.
*  I have basic knowledge of JavaScript.
*  I have a basic understanding of synchronicity and asynchrony, as well as the     concept of REST API.
*  I have a skill to write asynchronous code and requests to the server.
*  I have basic knowledge of the OOP paradigm.
*  I can work with Git through the terminal.

## Sample code (code taken from my work "Mesto"):
```
_setEventListeners() {
  const inputList = Array.from (this._form.querySelectorAll(this._data.inputSelector);
  const buttonElement = this._form.querySelector(this._data.submitButtonSelector);

  this._form.addEventListener('reset', () => {
    this._disabledBtn(buttonElement)
  })
  this._toggleButtonState(inputList, buttonElement);

  inputList.forEach(input => {
    input.addEventListener('input', () => {
      this._isValid(input);
      this._toggleButtonState(inputList, buttonElement);
    });
  })
}
```

## Work experience / study projects:
There are several projects in my portfolio, one of which is the "Mesto" project.
This project was carried out as part of the Yandex Praktikum. The language of the site is Russian. This site is made in the process of the study of adaptive layout, JavaScript, working with the API, as well as the principles of OOP. The project works on screen resolutions from 320px to 1280px. The BEM methodology was used. Grid technologies have been implemented. Added functionality using JS - modal windows are opened and closed, content is rendered on the page. The project was assembled using webpack. Link to the project: ['Mesto'](https://github.com/LiubovMavlieva/mesto-project )

*********
## Education:
*  Unfinished MFPU - profession "Web developer";
*  Yandex Workshop - front-end developer;
*  RS School stage0;

## Languages: 
*  Russian: Native;
*  English: B2;