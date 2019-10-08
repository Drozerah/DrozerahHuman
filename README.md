# Drozerah Human

A short piece of code to get in touch with me that I use in my projects. It is composed of an SVG icon nested with a link to [my GitHub profile](https://github.com/Drozerah) plus, informations directly coded as comments in the HTML.

```
<a href="https://github.com/Drozerah" class="drozerah" target="_blank" title="Drozerah web développeur - trouvez moi sur GitHub">
    <span>Drozerah</span>
    <!-- EN
        Hello, are you looking for a contributor for one of your web projects 
        or for the creation of your website? Feel free to contact me, 
        more information about me by following this link:
        https://myproject.com/humans.txt
    -->
    <!--
        Bonjour, vous recherchez un contributeur pour l'un de vos projets web
        ou encore, pour la création de votre site internet ? N'hésitez pas à me
        contacter, plus d'informations à mon sujet en suivant ce lien :
        https://myproject.com/humans.txt
    --> 
    <svg aria-label="simple github icon" role="img" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
        <path d="M12 .297c-6.63 0-12 5.373-12 12 0 5.303 3.438 9.8 8.205 11.385.6.113.82-.258.82-.577 0-.285-.01-1.04-.015-2.04-3.338.724-4.042-1.61-4.042-1.61C4.422 18.07 3.633 17.7 3.633 17.7c-1.087-.744.084-.729.084-.729 1.205.084 1.838 1.236 1.838 1.236 1.07 1.835 2.809 1.305 3.495.998.108-.776.417-1.305.76-1.605-2.665-.3-5.466-1.332-5.466-5.93 0-1.31.465-2.38 1.235-3.22-.135-.303-.54-1.523.105-3.176 0 0 1.005-.322 3.3 1.23.96-.267 1.98-.399 3-.405 1.02.006 2.04.138 3 .405 2.28-1.552 3.285-1.23 3.285-1.23.645 1.653.24 2.873.12 3.176.765.84 1.23 1.91 1.23 3.22 0 4.61-2.805 5.625-5.475 5.92.42.36.81 1.096.81 2.22 0 1.606-.015 2.896-.015 3.286 0 .315.21.69.825.57C20.565 22.092 24 17.592 24 12.297c0-6.627-5.373-12-12-12" class="path-name"/>
    </svg>   
</a>
```

In adition, the ```<head>``` contain an author tag to link a ```humans.txt``` file and give more informations about the author, the team or the project...

```
<link type="text/plain" rel="author" href="humans.txt" />
```

````
/* TEAM */

Developer: Thomas G.
                            
GitHub: https://github.com/Drozerah
                         
Location: France
                                        
/* SITE */
                           
Last update: 2018/04/30
                            
Standards: HTML5/CSS3/SCSS/JQuery/VanillaJS 
                            
Software: VScode, Gulp...
````

The internet is for humans ! If you want to learn more about the ```humans.txt``` file, you can go to [About humans.txt](http://humanstxt.org/).
