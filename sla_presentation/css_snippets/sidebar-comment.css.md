1.  Go to settings
2.  Go to appearance -> css snippets
```
/* Comments appears on the left sidebar*/

/* use '<!-- Comment -->' */

.cm-comment {

    position: absolute;

    left: -220px;  /* Space from left sidebar */

    color: #ffcc00; /* color for comments */

    font-size: 0.9em;

    max-width: 200px;

    pointer-events: auto; /* clickable comments */

}
```