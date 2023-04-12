<template>
  <div class="container">
	<div class="d-flex justify-content-center h-100">
		<div class="card">
			<div class="card-header">
				<h3>iniciar</h3>
			</div>
			<div class="card-body">
				<form>
					<div class="input-group form-group">

						<input type="text" class="form-control" placeholder="username">
						
					</div>
          <br>
					<div class="input-group form-group">

						<input type="password" class="form-control" placeholder="password">
					</div>
          <br>
					<div class="row align-items-center remember">
						<input type="checkbox">                siempre tu cuenta
					</div>
					<div class="form-group">
						<input type="submit" value="iniciar" class="btn float-right login_btn">
					</div>
				</form>
			</div>
			<div class="card-footer">
				<div class="d-flex justify-content-center links">
					no tengo una cuenta ?<a href="#">iniciar</a>
				</div>
				<div class="d-flex justify-content-center">
					<a href="#">olvidastes tu contraseña?</a>
				</div>
			</div>
		</div>
	</div>
</div>

</template>

<script>
export default {
  name: 'helloWorld',
  components:{


  },

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.container{
height: 100%;
align-content: center;
}

.card{
height: 370px;
margin-top: auto;
margin-bottom: auto;
width: 400px;
background-color: rgba(65, 93, 182, 0.5) !important;
}

.social_icon span{
font-size: 60px;
margin-left: 10px;
color: #FFC312;
}

.social_icon span:hover{
color: white;
cursor: pointer;
}

.card-header h3{
color: white;
}

.social_icon{
position: absolute;
right: 20px;
top: -45px;
}

.input-group-prepend span{
width: 50px;
background-color: #FFC312;
color: rgb(230, 158, 158);
border:0 !important;
}

input:focus{
outline: 0 0 0 0  !important;
box-shadow: 0 0 0 0 !important;

}

.remember{
color: white;
}

.remember input
{
width: 20px;
height: 20px;
margin-left: 15px;
margin-right: 5px;
}

.login_btn{
color: black;
background-color: #1aff12;
width: 100px;
}

.login_btn:hover{
color: black;
background-color: white;
}

.links{
color: white;
}

.links a{
margin-left: 4px;
}

</style>
