# client_side_captcha
This is a simple recaptcha js process that uses a random position of the clicked entry instead of a fixed position it only requires encoding and decoding and makes the backend language provide the random position numbers and the way to send the secure encrypted ajax request for validation by the backend using the provided position numbers, and unlike google captcha it's not element within iframe that can simple got by javascript and clicked it uses canvas shapes so no inpsect real not customized by iframe, even developer used this can not know what is the next position of the fake input

#### what it do more than recaptcha v2:
the idea based on to automate this you must use AI to process image and get poistions and back to app to automate click, no javascript or fixed position app clicker, note google captcha v2 uses div for input within iframe which by eye says it can inspeacted some how and 2 document.querySelector pass it

for check how simplly pass google recpatcha v2 check powershell scrape repo it contains fixed PS clicker that takes no time to pass and easy can started with selenuim when it see the captcha, but sure this less than v3 images but same level both requires AI but this simpler for user and hard for bot, but v3 take time even for normal user and keep searching for images match keyword and tons of codes to delay the automate (only issue client and server validtion that advanced developers can pass using same request, maybe in future they create something like webstorage for python for example can only accessed by client like pyJS.getValue(myData) and returned encyrpted, and pyJS.encyrptValue() that diffrent from any other server based on key or something, can also handled when jinja2 proccssed same time set something to pyJS hidden ) instead of {{12356}} , in js will be something like pyjs.getVal(), pyjs.decypt();, pyjs.encrypt, and in python pyjs.encrypt and pyjs.decyrpt (logical right now nothing do like this), is this very simple not like v3 require time from human to solve the images match you can set timeout for 1 second only so any human can click on the time and bot must take more than 1 second at least to import the large heavy AI module that process the image and back to selenum etc hard all that done in 1 second and it easy for human to solve in less than 1 second too. even in this way 1second it stronger than the image v3 as image v3 is static for the wait time but here it keeps moving and dynamic, so fast devices can overide image as it depend on wait for both human and bots, but this depend on human fast to detect the position and un element used so he must go to AI, but as said in begning this not completed and require backend and client side validation and encyrption so using google recptcha for now it's better and more secure but this repo for only display the idea that forces to handled by human or AI only

* added new feature for invalid clicks count that rechange the random position,

![image](https://github.com/MahmoudHegazi/client_side_captcha/assets/55125302/cad449ca-50e6-4a4e-b00d-6aff74f48883)

![image](https://github.com/MahmoudHegazi/client_side_captcha/assets/55125302/83b091c0-debf-4030-9f01-4eb7b8d04306)

after pass 7 seconds:

![image](https://github.com/MahmoudHegazi/client_side_captcha/assets/55125302/e450ab4d-145f-4200-a136-1ad0cca0178e)
