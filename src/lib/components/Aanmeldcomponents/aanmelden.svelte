
<form
	name="survey-form"
	action="https://formspree.io/f/xjvdkzdv"
	method="post"
>
	<fieldset id="fs-frm-inputs">
		<label for="full-name">Full Name</label>
		<input
			type="text"
			name="name"
			id="full-name"
			placeholder="First and Last"
			required="#"
		/>
		<label for="email-address">Email Address</label>
		<input
			type="email"
			name="_replyto"
			id="email-address"
			placeholder="email@domain.com"
			required="#"
		/>
		<fieldset >
			<label for="#"
				>Kies welke we love web sessie je wilt bijwonen</label
			>
			<select name="welovewebsessie" id="welovewebsessie" required="#">
				<option value="" selected="" disabled="">Choose</option>
				<option value="Decklan Reck ">We love web Why perfomance matters</option>
				<option value="Cyd Stumpel"> We love web navigeren op het web en de kracht van CSS</option>
				<option value="Ischa Gast"> We love web Toegankelijkheid op het web</option>
				<option value="Leonie Watson">ICONS vs We love web</option>
		</fieldset>
		<label for="message">Additional Comments</label>
		<textarea
			rows="3"
			name="message"
			id="message"
			placeholder="Heb je nog andere opmerkingen of vragen? Plaats dat dan hieronder"
			required="# "
		/>
		<input
			type="hidden"
			name="_subject"
			id="email-subject"
			value="Survey Responses"
		/>
	</fieldset>
	<button 
    type="submit"
    >Submit</button>
</form>


<style>
    form{
        padding: 2.5em;
    }
 form , fieldset {
    display: flex ;
    flex-direction: column;
    justify-content: start;
    gap: 1em;



    border: none;
    color: white;
    background-color: #050542;
}
form, input, select, textarea{
    border: #a675f5 1px solid;
    border-radius: 0.5rem;
    box-shadow: -0.3rem 0.3rem #a675f5;
}
input::placeholder{
    color: white;
}
select, textarea, input{
    padding: 1em;
    background-color: #050542;
    color: white;
}
fieldset ,input , select{
    color: white;
    margin-bottom: 1em;
}

button{
    color: white;
    background-color: transparent;
    border: #a675f5 1px solid;
    border-radius: 0.5rem;
    box-shadow: -0.3rem 0.3rem #a675f5;
margin: 2em;
padding: .5em;
}





</style>
