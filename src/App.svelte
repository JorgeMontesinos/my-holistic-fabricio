<script>
   import PsButton from './Button.svelte' ;
</script>
<div class = "card">
	<div class = "card">
		<h1> COMPONENTS </h1>
		<div class = "components">
		   <PsButton text="default Click"/>
		   <PsButton text="error" 			type = "error" />
		   <PsButton text="warning"  		type = "warning" />
		   <PsButton text="info"  			type = "info" />
		   <PsButton text="defaultr"  		type = "default" />
		   <PsButton text="error disabled"  type = "error" disabled = { true } />
		</div>
	 </div>
</div>

