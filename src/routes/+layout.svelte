<nav>
    <a href="/">home</a>
    <a href="/">about me</a>
    <a href="/">my work</a>
</nav>

<slot></slot>

<footer> © Jack Jackson 2020</footer>


<style>
* {
    font-family: 'Quicksand', sans-serif;
}

nav {
    background-color: #1f464d;
    display:flex;
    flex-direction: row-reverse;
    padding: 2em 10em;
}    

nav a {
    color: white;
    text-decoration: none;
    text-transform: uppercase;
    margin: 0em 3em;

}

nav a:hover {
    text-decoration: underline;
}

footer {
    color: white;
    text-align: center;
    margin-bottom: 6em;
}

@media only screen and (max-width: 850px) {

    nav {
    display:flex;
    flex-direction: row;
    padding: 2em 15em;
    }    

    nav a {
 
    margin: 0em 1em;

}

} 


@media only screen and (max-width: 767px) {
    nav {
    display:flex;
    flex-direction: row;
    padding: 2em 9em;
    }    

    nav a {

    margin: 0em 1em;

}



}

@media only screen and (min-width: 850px) and (max-width: 1800px) {
    nav {
    padding: 2em 3em;
    }    

    nav a {

    margin: 0em 1em;

}
	}


</style>