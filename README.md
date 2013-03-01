#pgFont 1.0.0


## What is this ?

pgFont is a very simple font containing the PostgreSQL logo.

pgFont is basically an extension of the Font Awesome project.

## I'm a Postgres DBA. Is this useful for me ?

Probably not. 

The goal of this font is to help web developpers who build websites related to Postgres. 
With a minimum of effort, they can integrate smoothly the PostgreSQL logo in their design.

This font should be helpful for Postgres community members creating websites with Twitter Bootstrap templates.

## Demo

see it live : http://daamien.github.com/pgfont/demo.html

## HTML Integration 

1- Download and install Font Awesome : http://fortawesome.github.com/Font-Awesome/

2- Install the pgFont.ttf file on your website and modify the font location in pgFont.css

3- Add the following lines to the page header
```
  <link rel="stylesheet" href="font-awesome.css">
  <link rel="stylesheet" href="pgFont.css">
```

4- You can now include the Postgres logo with this code 
```
  <p><i class="icon-pg-logo "></i> Slonik !</p>
```

5- Enjoy !


Note that pgFont supports IE7. See the Font Awesome website for more details. If you need this, I feel sorry for you.

## License 

- The PostgreSQL logo and the PostgreSQL trademark are copyrighted by the PostgreSQL Global Development Group (see Trademark Policy below)

- The font itself licensed under the PostgreSQL License 

##Trademark Policy

Please read : http://wiki.postgresql.org/wiki/Trademark_Policy

##Contact
- Email: damien@dalibo.com
- Twitter: http://twitter.com/daamien

##Changelog
- v1.0.0 - init 
