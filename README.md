# Project Title:LANDING PAGE

# Object: Old Language

# use 3 language to design web page:

1- HTML: 
* ADD SECTION NAME (div_data)
* Content  To th sections <h2> <p>
* <h5> in header section <header><nav>
* In <footer> change<p>&copy HAJAR ALTHUHLI.

2- Css: I make change in navbar_list style, and h5 with className (logo) and ul style.

3- JAVASCRIPT:
* changing text of h5 by use
document.getElementById("logo")& element.innerHTML = "LANGUAGE";

* call navigation bar
using addEventListener & function to call navlist
    document.querySelectorAll('section')
   document.getElementById('navbar__list')

 * create & add element to navigation bar
  -using function 
  -document.createElement('li')
  -document.createElement('a')
  -setAttribute by .getAttribute('data-nav')
  -using .appendChild(link) for creating links
       
  * scrolling and adding events for links
       -addEventListener('click', (event) => {}
       -getBoundingClientRect()

      