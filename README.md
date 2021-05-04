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

<h3>Day 1: address</h3>

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

Address example
💯 Check out <a href="https://nssdc.gsfc.nasa.gov/planetary/factsheet/">NASA's planetary fact sheet</a>,<br> 
which contains an old-school "address" tag near the bottom of the page.<br> 
Cheers to Dr. Dave Williams for using this tag correctly!

<hr>

<h3>Day 2: blockquote and q </h3>

"blockquote" is for block-level quotes.<br>
"q" is used for inline quotes.<br>

When to use "blockquote"<br>

✅ You're quoting an extended passage from a book, article, website, or some other work.<br>
    By making this passage stand alone, it's clear that this is something you are quoting, not something that you originally wrote.<br>

✅ You're quoting what someone said as a report, not as a conversation.<br>

✅ Somewhere, there's a citation that could go with this.<br>

When to use "q"<br>
🏁 You're quoting a short passage from a book, article, website, or another work. Typically this is a few words or a line or two. Anything longer should probably use blockquote.<br>

🏁 It's not a conversation.<br>

🏁 There's a citation that could go with it.<br>

When not to use "blockquote" or "q"
⛔️ Dialog - if it's a conversation, it's not a quote.<br>

⛔️ Sarcasm or "air quotes" - there is a double quote key on your keyboard for these. It's not just for "code."<br>

❌ ❌ ❌ PLEASE do not use <blockquote> for indents. CSS is made for indents. Use it.<br>

 Likewise, do not use <q> in particular for conversations.<br>
 It has built-in curly quotes before and after your quotation.<br>
 They're pretty and tempting. But they are not for your conversation.<br>

Did I mention that <q> is not for conversations?<br>
	
	
<hr>

<h4>Common attributes</h4>

👀 "cite" and the cite attribute are commonly associated with these elements, for obvious reasons.<br>
    Your original thoughts or writing are not included in "blockquote" and "q".<br>
    
    
    
<hr>
    
    
<h3>Day 3: "cite" </h3>

<b>cite</b> is for the title of a work, which can be quoted, referenced in detail, or mentioned in passing. 
"Works" are books, songs, paintings, programs, TV shows, operas, social media posts, and so much more. 
If you're referring to something that's not your own, you need to cite it in some way.

	Example:
	
	<p>Baby Yoda in <cite>The Mandalorian</cite> is the cutest thing ever!</p> 
	


<hr>

<h3>Day 4: "dfn" </h3>

"dfn" is used to indicate the term being defined within the context of a definition phrase or sentence.
Ways to use "dfn"
The most obvious usage is to indicate the term being described within the context of the phrase or sentence. Here,
"Godzilla" is defined by the rest of the paragraph.

	Example:
	<p>My son thinks he is <dfn>Godzilla</dfn>, who is generally depicted as an enormous, violent, prehistoric sea monster awakened and empowered by nuclear radiation. 		It's true, there are similarities.</p> 

<hr>

<h3>Day 5: "Description lists and ' dl ', ' dt ', 'dd' " </h3>


We focus on the three elements that make up a description list, historically called the definition list: 'dl', 'dt', and 'dd'.<br>

The meaning of each tag is as follows:<br>

'dl' description list (or definition list)<br>

'dt' description name (or definition term)<br>

'dd' description details (or definition)<br>

