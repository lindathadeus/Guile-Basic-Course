# Guile-Basic-Course
Basic Examples to get a hold on this language.

Remember to install guile, I am installing guile-3.0 and dev libraries and header files using the below steps

sudo apt install guile-3.0
sudo apt install guile-3.0-dev

Also, it would be helpful for us if we enable readline in guile interpreter, in order to using up and down arrow keys for recent commands

echo "(use-modules (ice-9 readline))" >> ~/.guile
echo "(activate-readline)" >> ~/.guile
