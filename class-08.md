chapter layout 
css treats with the html tags as block box 
we can control the postion schema  to control  the layout of css 
chapter 15 layout 
 *_*
 css trets html elements as boxes either it`s inline or block
 example for block leverl elements 
 <h1> <p><ul><li>
 example for inline is <img>
 <span> <b> <i></i>
 we can control  the postion of the lement in css with  some thing called postioning schemes :
 normal flow, relative positioning, and absolute
positioning
and to know where to put the box we have to use  box offset  proprties  either it`s Fixed Positioning or Floating Elements
we can put element beside each other using the float proprity  either its right or left 
##diffrent screen size 
each user ueses diffrent device and  the size of the screen is diffrent so we have to make our page flixable to fit each screen
and we should notice that the resualtion of each screen is diffrent 
fixed width layout 
when we use this the size of the lemetns does not change if we hange the size of the page minmize it or maxiamaze it and this have adv and dis Adv
the adv are :Pixel values are accurate
at controlling size and
positioning of elements.
1-The designer has far greater
control over the appearance
and position of items on the
page than with liquid layouts.
2- You can control the lengths
of lines of text regardless of
the size of the user's window.
3- The size of an image will
always remain the same
relative to the rest of the
page.
Floating Elements:Liquid layout designs
stretch and contract as the user increasesor decreases thesize of their browserwindow. They tend touse percentages.
Designers keep pages within 960-1000 pixels wide,and indicate what the site is about within the top 600pixels (to demonstrate its relevance without scrolling).
* Grids help create professional and flexible designs.
##chapter  3 in the javasript book 
its about fination and methods 
what is the fination 
its a olleation of statemetn that we put it togather to do a spefi task  and we an resue the funation so we dont have repeting in our code 
the funcation can accedpt parments or without and can have return statemt and it is exucted when we call it 
when we want to decale a fuinaction first we write 
function nameOfFunction()
{
    here we write the statements 
}
so after declaing the function it wont exucted until we call it and we call it by  the name of the function like this 
example : welcome();
sometime we need to give the finction some info to start working so we can do this by  giving the info to the parmenters 
function sum(mark1,mark2)
{
    return mark1+mark2;