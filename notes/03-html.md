# HTML
4/25/23
Head/Body/Footer
HEAD
! to start - template mode (esc)
    ->TITLE
Title ends up on webpage tab
link: favicon to fix icon on tab
    ->TITLE
after this, collapse head and move into body
LINK    TAB "STYLE.CSS"
HEAD

BODY
Body holds the header (not the head)
    ->HEADER
        -> <NAV class="d-flex align-items-baseline">        class defined in css
            -> DIV LOGO DIV       div*3 = 3 divs = logo, links, log in

            -> DIV Links DIV
            -> DIV Log In DIV       alt =
        -> <NAV>       
    ->HEADER
Main
    -> Section Class="banana"           ****Article tags group p tags! - Semantic Elements in HTML
        -> Div (Class="banana") Div
    -> Section

    -> Section
        (class="banana")
    -> Section

Main

FOOTER

FOOTER

Span only takes up the width of its content, Div takes up the whole BLOCK

4/26/23
.row enter creates the container
.col-6 *2 = creates columns within row
**section vs. div for Rows!
col-12 to 
col-md-4 (mobile to desktop)
class="img-fluid" img restricted by size of container
cntrl+/ = notes
class fw = font weight
text-center
<i> = icon class="mdi mdi-[whatever icon]
order-1 order-md-0
CDN = content delivery network
https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/css/bootstrap.min.css
https://cdnjs.cloudflare.com/ajax/libs/MaterialDesign-Webfont/7.2.96/css/materialdesignicons.min.css

Material Design Icons Intellisense by Lukas Troyer
Bootstrap 5 Quick Snippets by Anbuselvan Rocky

4/27/23
****Create a rough outline in HTML
!!!! class on element col-md-5 col-10 === column creation within rows 12 masx
! enter
HEAD
link bootstrap, mdi, etc., CSS 
BODY
section navbar
HEADER = container-fluid
section 
BODY
all the stuff !!!Div class "row"
SEction
MAIN
section
STUB = subsections
FOOTER
footer stuff
Once outline is complete, start working top to bottom

text-center will center an image inside of a column...justify-content won't always work.

5/1/23
.row / .col / .card / .card-body /.img / .p? .potion? to quick build!
.i for icon div (within p element)
onclick similar to class call in HTML
CAREFULLY name console logs for readability
Span keeps elements in the same line by default
don't use window.reload! 😊