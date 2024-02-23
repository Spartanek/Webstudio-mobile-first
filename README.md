# Webstudio-mobile-first

Перероблю макет технікою mobile-first

План:

1. Викачка картинок (1х, 2х) та svg проганяючи через squosh і тд;
2. Створення верстки;
3. Стилізація;
4. Стилізація відносно техніки mobile-first;
5. Додавання js елементів

   $name: #fff;
.welcome::before{
height:200px;
font-size:40;
content:'Привіт, #{$name}'
   }
      <!-- social - кожного разу коли буде цикл буде запускатись нове значення по-черзі -->

   @each $social in telegram, viber{
.#{$social}-icon{
   background-image: url('../#{$social}.png');
   }
   }
   layout
