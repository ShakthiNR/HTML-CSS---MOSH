# CODE WITH MOSH

## Part-1

```
1. Alt + up/down = to move text
2. select text then shift+alt+down = to copy nd paste the bunch of texts
```

```
3. border-collapse:collapse

4. object-fit:cover

5. Id: Unique to Tag
   Class: Can have in multiple tag

6. Selector:
   div > p{ } //style first child (<p>) inside parent(<div>)
   div + p{ } //style first <p> which immediately after div (sibling) 
   div ~ p{ } //style all <p> which are after div (sibling) 
```

```
7. Pseudo Class (:)

   .article :first-child { }
   ul li:nth-child(odd) { } 
   ul li:nth-child(3n) { }  //every 3rd
   a:visited { }
   div:hover { }
   a:hover, a:focus { }

8. Pseudo Element (::) - style part of element

   p::first-letter { }

   p::selection { } //select text give color

   p::before{
     content:"..."
   }

   p::after{
     content:"..."
   }
```

```
9. Selector Specificity --->   Id > Class > Element 

   #id .class { } //More specific than .class { }  and div { }


10. Gradient: www.cssgradient.io

11. Shadow:
    box-shadow: 0 0 30px grey
    text-shadow: 3px 3px 5px grey
```








