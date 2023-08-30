@Cuando("ingresa los datos correctamente")
 
public void ingresaLosDatosCorrectamente(List \<Credenciales\> datos) throws Exception{

theActorInTheSpotlight().attemptsTo(Loguearse.con(1,datos));
 
}
 
@Entonces("debe observar la pagina principal de sucursal virtual")

public void debeObservarLaPaginaPrincipalDeSucursalVirtual() throws Exception{

System.out.println("**** Finaliza la prueba exitosamente ****");

}
