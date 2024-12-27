<script>
  import Banner from "./lib/Banner.svelte";
  import Footer from "./lib/Footer.svelte";
  import Header from "./lib/Header.svelte";

  let fechaSorteo = `10 de Enero`
	let premioMayor = `MOTO AVA TIGRITO 175CC 2024 IMPECABLE`
	let rangoValue = $state(0);
    let numeross = $state([]);
	let nuevo = $state([]);
    let numerosInitialValue = $state(`9999`);
	let findNumber = $state([]);
	let totalZelle = $state('');

	let ticketValue = $state(20);
    let formData = $state({ });
	let numbersAvailable = $state([]);
	let selectedTicket = $state([]);
</script>

<main>
  <Header/>
  <Banner {rangoValue} {ticketValue} {formData} {nuevo}  {fechaSorteo}, {premioMayor} ,{totalZelle}, {findNumber} 
	{numbersAvailable}
	{selectedTicket}
	 />
   <Footer/>
  
</main>


