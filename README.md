# StickyNotesFreshman

    //// TO DOO
    
    //// enter text directly without the popup window prompt

    //// update z-index on newSticky so they take priority over an edited sticky

    //// really need better colors but didn't wanna spend too long
    //// also tweak the text and other visual stuff

    //// just an idea I want to work out how to get the area based on body height/width
    //// to set the number of 'pixels' to print in the for loop if body changes
    // let width = document.getElementById("peg").style.width;
    // let height = document.getElementById("peg").style.height;

    //// OBSOLETE
    //// was using this to make the board before
    //// was changing the properties of the clicked div to reshape it into a note
    //// position of the pixel didn't really matter, except it shifted all the others
    //// probably better to just make a new note at position which is currently applied in the code
    // function boardFunction()
    // {
    //     // for (i=1; i<area; i++) 
    //     for (i=0; i<600; i++) 
    //     {
    //         palette = ['sandybrown','rosybrown','tan','peru']
    //         color = palette[Math.floor(Math.random()*4)];
    //         document.getElementById("peg").innerHTML += '<div class="pixel" style="background-color: ' + color + ';" onmouseover="highlight(event)" onmouseleave="unhighlight(event)" onclick="newSticky(event)"></div>';
    //     }
    // }