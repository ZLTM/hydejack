---
layout: about
title: Contact
cover: true
image: /assets/img/glitchy_favicon.ico
---

<style>
//
#contact {
	max-width: 100%;
	margin: auto;
}

#contact p {
	text-align: center;
	font-family: helvetica, arial;
	font-size: 16px;
	font-weight: 200;
  color: white;
}


#card{
background: white;
	margin: auto;
	height: 400px;
	width: 100%;
	border: solid 3px black;
	position: relative;
	
}

#leftbox{
	float: left;
	width: 49%;
	overflow: hidden;
	
}

textarea {
	margin: 20px;
	border:none;
	resize: none; 
	font-size: 12px;
font-family: helvetica, arial;
}



#rightbox {
	float: right;
	width: 50%;

}


#send input{
	float: right;
	display: block;
	margin: 20px;
	height: 90px;
	width: 70px;
	background-color: #404040;
	color: white;
	border-style: none;
	border-radius: 5px;
	font-size: 16px;
	font-weight: bold;
	font-family: helvetica, arial;
	letter-spacing: 2px;

}

.line {
	margin-top: 10%;
	height: 340px;
	border-left: solid 1px black;
}

#input {
	padding-top: 180px;
}

#input input {
	margin: 20px 20px 40px 30px;
	display: block;
	width: 265px;
	font-size: 16px;
	border: none;
	border-bottom: dotted 2px black;
font-family: helvetica;
}
</style>
<body>
<div id="contact">
      <p>I'd love to get a message from you!</p>

      <div id="card">
        <form action="mailto:jdavidrevillad@gmail.com.com">
          <div id="leftbox">
            <textarea name="message" COLS="35" ROWS="16" placeholder="Your message" required></textarea>

          </div>
          <div id="rightbox">
            <div id="send">
              <input class="sendbutton" type="submit" value="Send">
            </div>
            <div class="line">
              <div id="input">

                <input type="text" name="name" placeholder="Name">
                <input type="email" name="email" placeholder="E-mail" required>
              </div>
            </div>
          </div>
        </form>
      </div>
		</div>
</body>