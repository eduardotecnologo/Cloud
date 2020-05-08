mutation MyMutation {
  	insert_user(
      objects:[
    		{ name:"Eduardo", email:"edudeveloperctk@gmail.com" }
 	 ]
    ){
    returning{
      id
      name
      email
    }
  }
}
