# Denis Salikhov

## Contact Info
* **Telegram:** @DenisDench
* **email:** salihov.den@mail.ru

## Summary
I started my front-end development selfeducation not that long ago, in November 2019. But I am ambitious and super motivated. I always learn something new from online courses, books and of course by google research. Ready to hit the wall. Ready to break it and hit another.

## Skills
* Basic knowledge of HTML/CSS/JavaScript
* Little experience with Sublime Text 3, VS Code, Command line

## Code examples

    ```css
        .circle {
            display: flex;
            position: absolute;
            justify-content: center;
            align-items: center;
            height: 32px;
            width: 32px;
            background-color: #8D6E63FF;
            border-radius: 18px;
            cursor: pointer;
        }
    ```
    ```javascript
        let leftOffset = 0;
		let topOffset = 0;
		let direction = "right";

		let moveHeading = function () {
			if (direction === "right") {
				$("#heading").offset({ left: leftOffset });
				leftOffset++;
				if (leftOffset > 200) {
					direction = "down";
					leftOffset = 200;
				}
			} else if (direction === "down") {
				$("#heading").offset({ top: topOffset });
				topOffset++;
				if (topOffset > 200) {
					direction = "left";
					topOffset = 200;
				}
			} else if (direction === "left") {
				$("#heading").offset({ left: leftOffset });
				leftOffset--;
				if (leftOffset < 0) {
					direction = "up";
					leftOffset = 0;
				}
			} else if (direction === "up") {
				$("#heading").offset({ top: topOffset });
				topOffset--;
				if (topOffset < 0) {
					direction = "right";
					topOffset = 0;
				}
			}
		};
		setInterval(moveHeading, 10);
    ```

## Experience
Absolutely no notable experience. Although you can visit my [google-homepage](https://github.com/DenisDench/google-homepage) repository which is my self-given challenge where I tried to copy the looks of Google homepage (just looks).

## Education
* [Codecademy](https://www.codecademy.com/profiles/DenisDench)
* Udemy
* Programming books

## English
* Pre-Intermediate