# demo
Quick list of projects

# Front-End

## [LearnHub](http://learnhub.esy.es/) (1 year project at Ecole Centrale de Lille)

Links :

- [website](http://learnhub.esy.es/)

- [repo](https://github.com/snwfdhmp/learnhub)

Description :

Social education tool for Ecole Centrale de Lille
You can take a tour by login with 'overview@github.com' / 'GitHub123'.
Feel free to do what you want, this is the TEST server.
    
# Back-End


## [Duck](https://github.com/snwfdhmp/learnhub)

### Links :

- [repo](https://github.com/snwfdhmp/duck)

### Description :

CLI for dev project managing. Duck provides its own file architecture to organize your code in the best way possible. It includes automatic fast compilation and comitting, unit testing, versioning, junk code management, git repo management, ...
I advice to read the README (click on **repo** link) which contains many informations about that project.
    
## [yt](https://github.com/snwfdhmp/yt)

### Links :

- [repo](https://github.com/snwfdhmp/duck)

### Description :

Command line tool for opening yt and do yt searches quickly from Terminal.
    
## [Top 1 GitHub (also called incCommit)](#)

### Links :

**NOT PUBLIC**

### Description :

Fun algorithm which permitted me to reach *Top 1 active developper* on GitHub on any account (I removed effects from my official account because it implies many many commits)
 
## [Humanity Evolution Modelisation](https://github.com/snwfdhmp/human-evolution-modelisation)

### Links :

- [repo](https://github.com/snwfdhmp/human-evolution-modelisation)

### Description :

C++ optimized tool for modelisation of human evolution (genetic) from generation to generation (25 millions/s on average).
The online project is limited to sex modelisation. For further informations, contact me at snwfdhmp@protonmail.com

## [PHP Web The New Way](https://github.com/snwfdhmp/php-framework)

### Links :

- [repo](https://github.com/snwfdhmp/php-framework) *The repo does not contain all the source code yet because it will probably be sold soon.*

### Description :

A PHP Framework built to provide a complete new way of writing PHP web app. Example : 
    
```PHP

    $app = new MainController("bootstrap");
    
    // Short and easily rememberable syntax
    $app.body(
        Tag::div( {class => 'container', id => 'root-container'},
            Tag::h1( "Welcome to my web app !" )
            .Tag::h2 ( "You can nest elements"
                .Tag::a("as easy as this"))));
    
    // Add headers at any place, nevermind if your server has buffer activated
    $app.header("Content-Type: text/html");
    
    // Never wonder again about placing elements in the right order, just say where you want it to be
    $app.body.before(
        Tag::span( {class => 'navbar'}
            "Some elements into my navbar")
            .$app::render("app-logo")); // Render ressources easily
            
    // Oops we forgot to include some CSS/JS ... nevermind
    $app.provide("angular.js", "dist"); // the app will automatically include JS from the best CDN
    $app.provide("style.css", "local"); // or include your files from the 'ressources/' directory
```

For further information, please contact me at snwfdhmp@protonmail.com

## [genetic algorithm](https://github.com/snwfdhmp/genetic-algorithm)

### Links :

- [repo](https://github.com/snwfdhmp/genetic-algorithm)

### Description :

Genetic algorithm for Object Conformism
    
## [Neural Networks](https://github.com/snwfdhmp/neural-networks)

### Links :

- [repo](https://github.com/snwfdhmp/neural-networks)

### Description :

Quick tries of deep neural network (number, function, lessOrGreater, word, and simple bit recognition)
    
## [Avalam AI Game](https://github.com/snwfdhmp/avalam-ai-game)

### Links :

- [repo](https://github.com/snwfdhmp/avalam-ai-game)

### Description :

While the UI is totally broken (we tried SDL but this is definetly something we don't work to work with), the back-end part with operator overload inheritance over abstract class polymorphism, may be interesting.
