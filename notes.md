Bkground Properties

#Background Attachment

Day-9 Font Property
1. Font Size:
    -->Default is 16px.
    -->Can change size of the font.
2. Font-Weight:
    (i) normal  (Default Value)
    (ii) bold
    iii light
    iv bolder
    v lighter
    vi 
    -->Values

3. Font-Style:
    i normal 
    ii italic
    iii oblique
4. Font-family:
    i. Generic (old)
        a. Serif
        b. Sans-Serif
        c. display
        d. monospace
        e. Handwriting
    ii. S

    Google Fonts
    DaFont


    14/11/2024 
    How to create boiler plate code
    =========================
    shift+alt+i  
    select all   
    one (,) after double quotes
    inside bracket properties space in double quotes
    settings>snippets>css or css.json>paste whatsapp code in file then save. * missing
    !!DONE

    shortcut is prefix:CSS

    #Vendor Prefix:
    #CSS Box Model:
            #Box-Sizing:
            --> Syntax  box-sizing: border-box;
            --> Border Box is prefrred for creating boxes.
            --> Dont use content box.
            --> Bordex Box : Outside to inside
            --> Content Box: Inside to outside.
                #Margin Property:
                -->Types of margin
                1.Margin-top
                2.Margin-left
                3.Margin-right
                4.Margin-bottom
                -->Shortcuts:
                1.Margin:10px; [For all sides]
                2.Margin: 10px 20px;[horizontal]
                        top     right
                        bottom  left
                3.Margin: 10px 20px 30px;
                        top    right bottom
                               left
                4.Margin: 10px 20px 0px 0px;
                5.Margin-inline: 10px; [left=right=10px]
                6.Margin-inline: 10px    20px;
                                 Margin  
                                 inline
                                 start
                7.Margin-block:10px;
                                      Top
                                      Bottom
                8.

    <!-- vw= ViewPort Width
    vh= ViewPort Height -->

    15/11/2024

    #Padding-Property
    1.Padding-top: ;
    2.Padding-right: ;
    3.Padding-bottom:
    4.Padding-left:
        -->Padding Shortcuts:
            1.Padding: 10px;
                     top right
                     bottom left
            2.Padding:10px 20px;
                      Top    Right
                      Bottom Left
            3.Padding:10px 20px 30px;
                      Top  Right Bottom
                           Left
            4.Padding:10px 20px  30px   40px;
                      Top  Right Bottom Left


        -->Padding-inline:10px;
                          Left=Right
           2.Padding-inline:10px 20px;
                            Left Right               
           3.Padding-block:10px;
                          Top=Bottom
           4.Padding-block:10px 20px;
                           Top  Bottom

    #Border-Property:-

    1.Border-width:15px;

    2.Border-Style:values(Solid,Double,Dotted,Dashed,Groove);

    3.Border-color:;

      -->Border Shortcuts:
        
        Border: 2px   solid  black;
                width style  color
    4.Border-Radius:

      -->Border-top-left-radius:5px;
      -->Border-top-right-radius:5px;
      -->Border-bottom-right-radius:5px;
      -->Border-bottom-left-radius:5px;  

        *Border Radius Shortcuts:
        1.Border-Radius: __ ;
                        EveryCorner
        2.Border-radius: __       __ ;
                         TopLeft  TopRight

        3.Border-radius: __       __          __ ;
                         TopLeft  TopRight    BottomRight
                                  BottomLeft

        4.Border-radius: ___   ___   ___   ___;


        Fancy Border Radius : Website

        SHAADI.COM CARDS


    18/11/2024
    
    #OverFlow Property:

    1.Overflow: Visible

    2.Overflow: Hidden

    3.Overflow: scroll

    4.Overflow: auto

      -->  for horizontal scroll bar

            whitespace: nowrap;
      --> to hide scroll bar
            scrollbar-width: none;

    #Box-Shadow Property:

    1.box-shadow: +- 20px    //default color :black

                  h-offset  v-offset  blur    spread
                                      radius  radius  


    #Display Property:

    1. inline

    2. block

    3. inline-block
               -->by default space between box
    4. none

    5. flex

    6. inline-flex

    7. grid

    8. inline-grid

19/11/2024

Flex 

1. Flex Container Propert/Flex parent property:
    --> is applied on the container/parent not on the items.
    -->
        (a) display: flex;
            --> it is one dimension layout module.
            --> works on main axis.
            --> flex direction property by default gets applied 
                flex-direction: row;

        (b) flex-direction: _____  ; //it sets/defines main axis
            --> row(default)  //defines that x axis is main axis
            --> column        //defines that y axis is main axis
            --> row-reverse   //right to left
            --> column-reverse //bottom to top

        (c) flex-wrap:  ;
            (i) nowrap (default)

            (ii) wrap

            (iii) wrap-reverse


20/11/2024

        (d) flex-flow: flex direction and flex wrap can be applied together using this 
                        its a shortcut.
                       _______________    ________;
                       flex-direction     flex wrap
        
        (e) gap: _____ _____;
                 row   column
                 gap   gap

                 __________;
                 column gap
                 row gap         
        
        (f) justify-content: with respect to main axis
                            ________;

                        (i)flex-start; (by default)

                        (i)flex-end;

                        (iii) center;

                        (iv) space between

                        (v) space around

                        (vi) space evenly

                        (vii) align-item:; with respect to cross axis(axis other than main axis)
                                        a stretch (default)
                                        b flex-start
                                        c flex-end
                                        d center


22/11/2024

        Flex-Item Property:
        -> works on item

            1. flex-basis: px,%,rem;
                with respect to main axis

            2. Order: 1,2,3....;

            3. align-self: 
                          strech
                          flex-start
                          flex-end
                          center
            4. fel-grow:              
                         
25/11/2024

        Display Grid:
           --> display: grid

           1.Grid Container
           
           2. Grid Items

           3. Grid Column Line

           4. Track

           5. Grid Area

        --> Difference between Flex and Grid:

                Flex                            Grid
            1. Dimension
             
             It is a 1D layout module 
                                                 . It is 2D layout module

        --> Grid Container Property

            1. display: ;
                        i. grid
            
                        ii. inline grid


            2. grid-template-rows: ;
                                i. 100px 100px 100px
                                ii. repeat(no of rows, size of row)

            3. grid-template-column: ;
                                    i.repeat()

            4. gap:
                    i. row gap    colum gap

            5. justify-content:
                               i. stretch
                               ii. start
                               iii. end
                               iv. center
                               v. space-between
                               vi. space-around
                               vii. space evenly
            
            
            6. align-content:
                             i.stretch
                             ii. flex-start
                             iii. flex-end
                             iv. center
                             v. space-between
                             vi. space-around
                             vii. space-evenly

            7. justify-items: 
                                i. stretch
                                ii. flex-start
                                iii. flex-end
                                iv. center
            8. align-items:
                                i.stretch
                                ii.flex-start
                                iii. flex-end
                                iv. center

            9. place-content: 
                                align-content    justify element;
            
            10. place-items: 
                                align items       justify items;


    26/11/2024

             grid-template-rows/columns <mandatory>

            11. grid-template-areas: ;
                                     i. .(empty)
                                     ii. "header header header"
                                        "section section aside"
                                        "menu . aside"
                                        "footer footer footer"

               grid-area:  header ;  <in children>                 


    27/11/2024

                Position Property:
                    --> Little adjustments
                     --> default value: static 
                         change it to relative to make it moveable.  
                    to make change position with respect to container or anything mark that parent as

                    {
                        position: relative;
                    }          


     28//11/2024
            position property:
                                fixed:used for nav bars

                                Z-index
                                -->                

                    designer tool extension --> exact properties used in a website
                    css peeper extension
                    bootstrap icon <link tag copy paste in header>
    

    29/11/2024 

            <svg viewbox="">  //used to draw shapes

                circle 
                red
                square
                <path d=" "   fill="black" stroke=" color "
                        stroke-width= "4" >

            </svg>    