# rsschool-2019Q1-cv
My resume
### 1. First name, last name
  Alexey
  Fedorovcih
### 2. Contacts
   - mobile phone: +375 (33) 695-04-79 mts;
   - instagram: fedomladshi;
   - vk: Lesha Fedorovich.
### 3. Summary 
   I appreciate the sense of purpose and discipline in people, I think for a programmer these skills are very important, so I try to     follow them. I study web development for a year on my own, and to test my knowledge I take part in these courses. Ready to work under pressure and to tight deadlines, communicate confidently and me up with solutions to seemingly intractable problems. My goal is to become better and take the place of a front-end developer.
### 4. Skills
Good knowledge HTML5 and СС3. Have experience in creating responsive sites using bootstrap 4 or just flexbox, js/query, according to the methodology BEM. Knowlegde of C++, C# (thanks to college). Understanding OOP.
### 5. Code examples
##### JS
I tried to make a game, but as it turned out it's not so easy)
```sh
function move() {
    let snakeCoordinates = [snakeBody[0].getAttribute('posX'), snakeBody[0].getAttribute('posY')];
    snakeBody[0].classList.remove('head');
    snakeBody[snakeBody.length - 1].classList.remove('snakeBody');
    snakeBody.pop();
    if (snakeCoordinates[0] < 10) {
        snakeBody.unshift(document.querySelector('[posX = "' + (snakeCoordinates[0] + 1) + '"][posY = "' + snakeCoordinates[1] + '"]'));
    } else {
        snakeBody.unshift(document.querySelector('[posX = "1"][posY = "' + snakeCoordinates[1] + '"]'));
    }
    snakeBody[0].classList.add('head');
    for (let i = 0; i < snakeBody.length; i++) {
        snakeBody[i].classList.add('snakeBody');
    }
}
The following examples are small pieces of code from one of the sites
```
##### HTML
```sh
<section class="section-1">
    <div class="container">
      <div class="section-1__content">
        <div class="section-1__article">
          <h3 class="Title">this is bouncy</h3>
          <p class="text text_w-1"> Lorem ipsum dolor sit amet consectetur adipisicing elit. Veritatis voluptas fuga
            nihil aut vitae soluta. Illum saepe id maxime quibusdam quisquam assumenda dolor nam soluta repellat,
            tempore perferendis in tenetur? Maiores vero magnam corporis nihil ipsa vitae ullam minima necessitatibus
            dignissimos. Vel, tenetur rem non saepe adipisci, accusantium voluptas.</p>
          <a class="section-1__button section-1__button-text" href="#">
            Read more
          </a>
        </div>
        <div class="section-1__picture">
          <img class="section-1_ipad" src="./images/IPAD.png" alt="ipad">
        </div>
      </div>
    </div>
```
### CSS
```sh
.header-next__circle:hover {
	box-shadow: 0 0 50px rgba(255, 255, 255, 0.8);
	background-color: rgb(38, 209, 172);
}

.fa_arrow-size {
	font-size: 16px;
	color: rgb(255, 255, 255);
}

.header-menu__bar {
	position: relative;
	top: 12px;
	right: 15px;
	font-size: 1.5rem;
	color: rgb(207, 207, 207);
	display: none;
}

@media screen and (max-width: 768px) {
	.header-menu__navigation_hidden {
		display: none;
	}

	.header-menu__bar {
		display: block;
	}
}
```
