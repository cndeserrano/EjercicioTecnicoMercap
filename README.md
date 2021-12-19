Buenos dias/tardes a quien corresponda,
A continuacion esta el codigo hecho siguiendo las indicaciones que me enviaron, utilice el lenguaje Smalltalk aplicando TDD.
El trabajo es bastante simple de seguir, pero quisiera aclarar la manera de ver por pantalla como sería una factura en playgorund, la cual es la siguiente:


	sistema := Sistema new.
	
	sistema registrarUsuario: 'Diego' conPlan: 100.
	usuario := sistema obtenerUsuario: 'Diego'.
	usuario nuevoMes: 'Septiembre'.
	
	usuario crearLlamadaLocalDe: 3 MinutosElDia: 'Viernes' aLas: 10.
	sistema mostrarFactura: usuario enElMes: 'Septiembre'.
  
  
  
este es un ejemplo basico con un solo cargo, puede tener varios o ninguno, igual va a funcionar.
