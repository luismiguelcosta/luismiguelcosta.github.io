Hi all :)

This is a draft of the personal website I'm planning to create for me.

Until now I'm playing with Bootstrap and I'm using for the first time the .order-(breakpoint) class to organize differently the website blocks, according to the screen size.

If you want to change the look and feel, execute the following procedure.

Procedure to install Css compiler and compile Scss to Css automaticly after every time you save the .scss file:
  - go to the right folder (in this case the costaluis-website folder);
  - if you don't have Sass instaled, do it in the terminal with this command line: npm install -g sass (with npm installed);
  - then to start the automatic compiler, use this command line in the terminal: sass --watch main.scss css/main.css
