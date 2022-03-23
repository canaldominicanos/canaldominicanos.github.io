---
layout: default
title: Home
published: true
---

<!-- One -->
<section id="one" class="wrapper style2 special">
	<header class="major">
		<h2>Te damos la Bienvenida a Nuestro canal<br />
		#Dominicanos ven y disfruta con nosotros!!!</h2>
	</header>
</section>

<section id="one" class="wrapper style2 special">
	<header class="major">
		
		<h3>AVISO DEL STAFF</h3>
      <p> Quieres ser operador de #Dominicanos envianos un email con tu Nick y Porque crees que debes ser operador al correo <a href="mailto:canaldominicanos@gmail.com">canaldominicanos@gmail.com</a></p>
		
	</header>
</section>

<!-- Read the Formbutton docs at formspree.io/formbutton/docs. See more examples at codepen.io/formspree -->
<script src="https://formspree.io/js/formbutton-v1.min.js" defer></script>
<script>
  /* paste this line in verbatim */
  window.formbutton=window.formbutton||function(){(formbutton.q=formbutton.q||[]).push(arguments)};
  /* customize formbutton below*/     
  formbutton("create", {
    action: "https://formspree.io/f/myyopqlw",
    title: "Tienes alguna Pregunta para el Staff?",
    fields: [
      { 
        type: "email", 
        label: "Email:", 
        name: "email",
        required: true,
        placeholder: "tuemail@correo.comm"
      },
      {
        type: "textarea",
        label: "Message:",
        name: "message",
        placeholder: "Que tienes que compartirnos?",
      },
      { type: "submit" }      
    ],
    styles: {
      title: {
        backgroundColor: "gray"
      },
      button: {
        backgroundColor: "gray"
      }
    }
  });
</script>

<!-- Two -->
<section id="two" class="wrapper">
	<div class="inner alt">
		<section class="spotlight">
			<div class="image"><img src="u2pop.jpg" alt="" /></div>
			<div class="content">
				<h3>_u2pop_</h3>
				<p>Fundador del canal, veterano de irc desde la famosa red Undernet.</p>
			</div>
		</section>
		<section class="spotlight">
			<div class="image"><img src="avatar.jpg" alt="" /></div>
			<div class="content">
				<h3>Dev1ls</h3>
				<p>Co-Fundador del canal, veterano de irc, ayudante de Moderadores del canal #Dominicanos.</p>
			</div>
		</section>
		<section class="spotlight">
			<div class="image"><img src="guachiman.jpg" alt="" /></div>
			<div class="content">
				<h3>GuachiM4n</h3>
				<p>Co-Fundador del canal #Dominicanos, hacker de profesion, es el que vela por que todos nuestros chats sean seguros.. :)</p>
			</div>
		</section>	
	</div>
</section>
