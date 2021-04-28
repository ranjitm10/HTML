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

- A Block-level element occupies the entire horizontal space of its parent element (container), and vertical space equal to the height of its contents.
- Refer this <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ol#attributes">doc</a> for the different supported types.

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
            
- The <b>table</b> tag is a wrapper for the table.<br>
- The <b>thead</b> tag encloses the head of the table.<br>
- The <b>tbody</b> tag encloses the body of the table.<br>
- The <b>tr</b> tag encloses each row of the table.<br>
- The <b>th</b> tag encloses each cell of the table header.<br>
- The <b>td</b> tag encloses each cell of the table body.<br>

Follow this <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/table">doc</a> for more details about the <b>table</b> element.

<h1>30DaysofHTML</h1>

<hr>

<h3>Day 1: <address></h3>

<h4>What does <address> do?</h4>
   
"address" should be used for addresses. You guessed that already.<br> 
But what kind of addresses, and in what context?
   
<h4>Address context:</h4>
	

"address" was originally used to indicate contact information for the page owner.<br> 
It has since evolved to include any type of contact information, generally the address of an article author or the address of a website.

🔹 If "address" is placed within an <article>, it is assumed this is the article <b>author's address</b>.

🔸 If "address" is placed closest to the <body> tag, it's assumed to be the <b>website organization's address</b>.<br>
   Usually this type of information is found in a page header or footer.
	
<h4>Kinds of addresses</h4>
✅ Any information that's used to contact the website organization or the article author is fair game. That might include:<br>

-email addresses<br>

-social media links<br>

-phone numbers<br>

The contact person's name may also be included in an address element.<br>

⛔️ However, non-contact information is to be avoided.<br>
