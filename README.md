<h1>HTML</h1>

## Basic HTML

<hr>

<h3>Introduction</h3> :-

   - HTML (HyperText Markup Language) is the language in which websites are written. They form the skeleton of the websites, storing the content in a structured manner.
   - HTML blocks are building blocks of HTML pages. HTML allows us to add a variety of objects to a web page including tables, images, videos, forms, etc.

<hr>

<h3>Intro & Inline Elements</h3> :
            The simplest way to write HTML is just to write some text inside Elements.
            
        <br>, <b>, <i>, <u>, <sup>, <sub>, <code>, <a> are all rendered as inline elements.
  
  These elements render on the same line and do not break the flow of content.
            
            
<hr>

<h3>Block Elements</h3> :

1- The heading tags are h1, h2, h3, h4, h5 and h6<br>
2- The pragraph tags are p<br>
3- Lists - a) orderList <ol> <li></li> </ol>   b) unordered List <ul> <li><li> </ul> <br>
4- Blockquote - The HTML <blockquote> element indicates that the enclosed text is an extended quotation. Usually, this is rendered visually by indentation.<br>
5- Preformatted Text:
     The HTML element represents preformatted text which is to be presented exactly as written in the HTML file. <br>
     The text is typically rendered using a monospace font. Whitespace inside this element is displayed as written. <br>
            
            Example:
            
            <pre>A B   C
            D E   F G
            H I</pre>
            
      <h1> - <h6>, <p>, <ul>, <ol>, <li>, <hr>, <blockquote>, <pre> all represent block level elements.

A Block-level element occupies the entire horizontal space of its parent element (container), and vertical space equal to the height of its contents.

<hr>

<h3>Media And Tables</h3> :

1- Images - Images are displayed using the <img> tag.<br>
            They need the src attribute for the source of the image.<br>

           Example:
           
           <img src="https://workat.tech/images/At-144x144.png alt="workat.tech logo"/>
           
           
2- Video - You can embed videos in your web pages using the <video> tag.<br>
           It takes in an src attribute with the source of the video.
   
           Example:
           
           <video src="https://workattech-learning-html.netlify.app/public/media/videos/video.mp4"
    height="300px" controls></video>
    
3- Audio - You can embed audio in your web pages using the <audio> tag.<br>
           It takes in an src attribute with the source of the audio.
   
            Example:
            
            <audio src="https://workattech-learning-html.netlify.app/public/media/audio/audio.mp3" controls></audio>
            
            
4- Tables - HTML lets you add tables on your web pages using the <table> tag.<br> 
            This lets you add two-dimensional data to the website in a structured way comprised of rows and columns.
   
            Example:
            
            <table>
                 <thead>
                     <tr>
                        <th>Column 1</th>
                        <th>Column 2</th>
                        <th>Column 3</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>Data 11</td>
                        <td>Data 12</td>
                        <td>Data 13</td>
                    </tr>
                    <tr>
                        <td>Data 21</td>
                        <td>Data 22</td>
                        <td>Data 23</td>
                    </tr>
                    <tr>
                        <td>Data 31</td>
                        <td>Data 32</td>
                        <td>Data 33</td>
                    </tr>
                </tbody>
            </table>
            
- The <table> tag is a wrapper for the table.
- The <thead> tag encloses the head of the table.
- The <tbody> tag encloses the body of the table.
- The <tr> tag encloses each row of the table.
- The <th> tag encloses each cell of the table header.
- The <td> tag encloses each cell of the table body.

Follow this <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/table"> for more details about the <table> element.
