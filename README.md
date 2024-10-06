# Linkedin-Full_Stack

Html: Jen Simmons
    Content:
        Basics and Syntax of Html elements
        Formatting content 
        Displaying images 
        Creating Links 
        Global HTML attributes
        Building Navigation 
        Structuring Content
        Building Forms
        Creating Tables 

    Notes & Syntax:    
        Lists
            -Ordered list
                syntax:  <ol></ol>
            -Unordered list
                syntax:  <ul></ul>  
            -Definition List
                syntax:Defines the Key:Value pair of items 
                         <dl>
                            <dt>Term</dt>
                                <dd>defination</dd>
                                <dd>defination</dd>
                            <dt>Term2</dt>
                                <dd>defination</dd>
                                <dd>defination</dd>
                         </dl>
                         
        Quotes
            syntax:  <q></q>
            inline Elements
                <q>
                <strong>
                <b>
                <i>
                <em>
                <code>
            Block Level Elements
                <blockquote>
                <p>
                <ul>

        Time Date Element
            syntax:  <time>May 8,2024</time>
            
            using attributes: <time datetime="2024-05-08">May 8,2024</time>
            
            Date: YYYY-MM-DD

            Time: hh-mm-ss.ddd    [note: Stored in 24 hrs format]


        Code pre and br
            &lt:  <
            &gt:  >

        subscript,Superscript and small text
            Syntax:  H<sub>2</sub>O
            Syntax:  2sup>2</sup>
            Syntax:  <small>&copy;<small>

        HTML Attributes
            class
            id
            lang
            dir

        ARIA role

        Link
            Syntax:  <a href="Link_here">Click Here</a>

        Images
            Syntax: <img src="" alt="" width="" height=""
                    srcset="url1.jpg 2x, url2.jpg 3x">
                    <Figure><Figcaption>

        Audio
            Syntax: <audio controls src="" loop autoplay></audio>

        Video
            Syntax:  <video></video>

        Caption & Subtitles
            Syntax: <track src="" kind="captions" label="English" srclang="es" default>
                    <track src="" kind="subtitles" label="Espanol" srclang="es" >

        Embedding other media through iframes

        Tables 


CSS: Cristina Truong
    
    Types:
        inline
            Syntax:  <p style="color:red;font-size:12px;">Red Text</p>

        internal 
            This is added to the Head section of the HTML file
            Syntax:  p{color: red;}

        External
            The link of the external CSS file is added in the head of the HTML file 
            syntax:
                    <head>
                        <link rel="stylesheet" href="file_path">
                    </head>

    Pseudo classes/ Elements

    Specificity
    
    Key words
        !important