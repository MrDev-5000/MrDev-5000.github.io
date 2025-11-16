
<!DOCTYPE html>
<html lang = "en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Home</title>
        <style>
          * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    background-color: rgb(0, 0, 8);
    color: #00ff88;
    font-family: monospace;
    margin: 0;
    padding: 2rem;
    overflow-x: hidden;;
}

.header {

    background-color: black;
    width: 100%;
    text-align: center;

    border-style: solid;
    box-sizing: 0px;
    border-color:  transparent;
    border-radius: 15px;
    box-shadow: 0 0 10px rgba(102, 0, 255, 0.5), 0 0 20px rgba(0, 0, 255, 0.3), inset 0 0 10px rgba(111, 0, 255, 0.9);
    margin-bottom: 20px;
}

.header:hover  {
    transition: 1000ms;
   border-style: solid;
    box-sizing: 0px;
    border-color:  transparent;
    border-radius: 15px;
    box-shadow: 0 0 10px rgba(255, 132, 0, 0.5), 0 0 20px rgba(255, 0, 0, 0.3), inset 0 0 10px rgba(255, 0, 0, 0.968);    
     
}

.header_text {
    color: #00ff88;
    font-size: 2.5vmin;
    text-transform: uppercase;
    padding: 1rem;
}

.header_text:hover {
    color: rgb(0, 255, 119);
    text-shadow: 2px 2px 4px black, 0 0 40px rgb(4, 255, 0), 0 0 10px rgb(0, 255, 153)
}

.row {
    height: 10vh;
    display: flex;
}

.border {
    
    width: 8%; 
    height:600px;
    left:0px;

    border-style: solid;
    box-sizing: 0px;
    border-color:  transparent;
    border-radius: 15px;
    box-shadow: 0 0 10px rgba(102, 0, 255, 0.5), 0 0 20px rgba(0, 0, 255, 0.3), inset 0 0 10px rgba(111, 0, 255, 0.9); 
    
}

.content {
    float : right;
    width:90%;
    height: 600px;
    padding: 1rem;
    margin-bottom:20px;
    border-style: solid;
    box-sizing: 0px;
    border-color:  transparent;
    border-radius: 15px;
    box-shadow: 0 0 10px rgba(102, 0, 255, 0.5), 0 0 20px rgba(0, 0, 255, 0.3), inset 0 0 10px rgba(111, 0, 255, 0.9);    
}

.content_text {
    color: #00ff88;
    
}

.footer {
    clear:right;
    background-color: black;
    color: whitesmoke;

    width: 100%;

    text-align: center;
    text-transform: uppercase;

    border-style: solid;
    box-sizing: 0px;
    border-color:  transparent;
    border-radius: 15px;
    box-shadow: 0 0 10px rgba(102, 0, 255, 0.5), 0 0 20px rgba(0, 0, 255, 0.3), inset 0 0 10px rgba(111, 0, 255, 0.9);    
    padding: 1rem;
}

.footer:hover {
    transition: 1000ms;
   border-style: solid;
    box-sizing: 0px;
    border-color:  transparent;
    border-radius: 15px;
    box-shadow: 0 0 10px rgba(255, 132, 0, 0.5), 0 0 20px rgba(255, 0, 0, 0.3), inset 0 0 10px rgba(255, 0, 0, 0.968);    
     
}
.footer_text {
    color: #00ff88;

} 
        </style>
    </head>
    <body>

        <div class = "header">
            <p class = "header_text">WELCOME TO FORTerminal</p>
        </div>

        <div class = "content">
                <p class = "content_text">This is a terminal portfolio for developers. It showcases various skills and projects in a terminal-like interface.</p>
                <p class = "content_text">Explore the links below to learn more about the projects and skills.</p>
                <p class = "content_text">You can also find the source code on <a href="#"></a>GitHub</p>
                <p class = "content_text">Feel free to reach out for collaborations or inquiries.</p>
                <p class = "content_text">Thank you for visiting!</p>
        </div>
         
        <div class = "border">
            
        </div>
        
       
        <div class = "footer">
            <p class = "footer_text">© </p>
            <p class = "footer_text">All rights reserved</p>
        </div>
        
    </body>
</html>
