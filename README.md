# Beastify-extension
Adds a browser action icon to the toolbar. Click the button to choose a beast. The active tab's body content is then replaced with a picture of the chosen beast.


Note:Please note that this will work only under firefox if you are aiming to trying to run in chrome you should change according to that browser
The correct file heirarchy is :


beastify/

    beasts/
        frog.jpg
        snake.jpg
        giraffe.jpg

    content_scripts/
        beastify.js

    icons/
        beasts-32.png
        beasts-48.png

    popup/
        choose_beast.css
        choose_beast.html
        choose_beast.js

    manifest.json
