<script>
  export let text = 'click' ;
  export let type = 'default' ;
  export let disabled = false ;
  $: isDisabled = disabled? 'disable' : '' ;  
</script>

<button class = "btn {type} {isDisabled}" > { text } </button >

<style>
	.btn{
	  
	  color: #fff;
	  text-align: center;
	  letter-spacing: .5 px;
	  transition: background-color .2 s ease-out;
	  cursor: pointer;
	  font-size: 14px;
	  outline: 0 ;
	  border: none;
	  border-radius: 2px;
	  display: inline-block;
	  height: 36px;
	  line-height: 36px;
	  padding: 0 16px;
	  text-transform: uppercase;
	  vertical-align: middle;
	  -webkit-tap-highlight-color: transparent;
	  margin: 10px;
	}
   

.default 	{background-color: #26a69a;}
.error 		{background-color: #e43d3d;}
.warning 	{background-color: #c3bd43;}
.info 		{background-color: #2599e4;}
.disable {
	pointer-events: none;  opacity:.4 ;
}
</style>
	