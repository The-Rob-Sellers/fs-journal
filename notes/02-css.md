# CSS
4/25/23
:ROOT{
    --PAGE-BG: #FFF6F0
    --PRIMARY: #713EDD    root = "false element" this is where variables pull from
    --TEXT: 
    --ACCENT:
}

/* TYPICALLY you need this for calculating the boarder within the width: */
*{                          * applies to all elements
    box-sizing: content box
}

BODY{
    MARGIN: 0;
    BACKGROUND-COLOR: VAR(--PAGE-BG);
    COLOR: VAR(--TEXT);
    DISPLAY: FLEX; 
    FLEX-DIRECTION: COLUMN;
    MIN-HEIGHT: 100VH;  vh = view height
}
MAIN{
    FLEX-GROW: 1; FLEX-GROW = RATIO ie 1:1 or 2:1
}

.dark{
    background-color: var(--text);
    color: var(--page-bg);
}

.d-flex{
    display: flex;
    flex-wrap: wrap;       *mobile optimization
}

.align-items-center{
    align-items: center
}

.align-items-baseline{
    align-items: baseline
}

.justify-content-between{

}

.nav-logo{

}

/* MAIN SECTION */
.left {
    max-width: 46%;
    margin:
}