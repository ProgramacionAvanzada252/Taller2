# Taller2

public class zonde {
	
	private String infoPlaneta;
	private String infoCLiente;
	private String infoVehiculo;
	
	public zonde(String infoPlaneta, String infoCLiente, String infoVehiculo) {
		super();
		this.infoPlaneta = infoPlaneta;
		this.infoCLiente = infoCLiente;
		this.infoVehiculo = infoVehiculo;
	}

	public String getInfoPlaneta() {
		return infoPlaneta;
	}

	public String getInfoCLiente() {
		return infoCLiente;
	}

	public String getInfoVehiculo() {
		return infoVehiculo;
	}

	public void setInfoPlaneta(String infoPlaneta) {
		this.infoPlaneta = infoPlaneta;
	}

	public void setInfoCLiente(String infoCLiente) {
		this.infoCLiente = infoCLiente;
	}

	public void setInfoVehiculo(String infoVehiculo) {
		this.infoVehiculo = infoVehiculo;
	}
	
	
	
	
	

}//Fin class zonde

public class clienteRegular {
	
	private String nombre;
	private String rut;
	private String fechaDeNacimiento;
	private int dineroDisponible;
	private int distanciaPlaneta;
	private String planetaDestinoCR;
	private int rango;
	
	public clienteRegular(String nombre, String rut, String fechaDeNacimiento, int dineroDisponible,
			int distanciaPlaneta, String planetaDestinoCR, int rango) {
		super();
		this.nombre = nombre;
		this.rut = rut;
		this.fechaDeNacimiento = fechaDeNacimiento;
		this.dineroDisponible = dineroDisponible;
		this.distanciaPlaneta = distanciaPlaneta;
		this.planetaDestinoCR = planetaDestinoCR;
		this.rango = rango;
	}

	public String getNombre() {
		return nombre;
	}

	public String getRut() {
		return rut;
	}

	public String getFechaDeNacimiento() {
		return fechaDeNacimiento;
	}

	public int getDineroDisponible() {
		return dineroDisponible;
	}

	public int getDistanciaPlaneta() {
		return distanciaPlaneta;
	}

	public String getPlanetaDestinoCR() {
		return planetaDestinoCR;
	}

	public int getRango() {
		return rango;
	}

	public void setNombre(String nombre) {
		this.nombre = nombre;
	}

	public void setRut(String rut) {
		this.rut = rut;
	}

	public void setFechaDeNacimiento(String fechaDeNacimiento) {
		this.fechaDeNacimiento = fechaDeNacimiento;
	}

	public void setDineroDisponible(int dineroDisponible) {
		this.dineroDisponible = dineroDisponible;
	}

	public void setDistanciaPlaneta(int distanciaPlaneta) {
		this.distanciaPlaneta = distanciaPlaneta;
	}

	public void setPlanetaDestinoCR(String planetaDestinoCR) {
		this.planetaDestinoCR = planetaDestinoCR;
	}

	public void setRango(int rango) {
		this.rango = rango;
	}

	
	
	
	}
	
	

}//Fin class cliente regular

public class clienteCriminal {
	
	private String nombre;
	private String rut;
	private String fechaDeNacimiento;
	private String planetaDestinoCC;
	
	public clienteCriminal(String nombre, String rut, String fechaDeNacimiento, String planetaDestinoCC) {
		super();
		this.nombre = nombre;
		this.rut = rut;
		this.fechaDeNacimiento = fechaDeNacimiento;
		this.planetaDestinoCC = planetaDestinoCC;
	}

	public String getNombre() {
		return nombre;
	}

	public String getRut() {
		return rut;
	}

	public String getFechaDeNacimiento() {
		return fechaDeNacimiento;
	}

	public String getPlanetaDestinoCC() {
		return planetaDestinoCC;
	}

	public void setNombre(String nombre) {
		this.nombre = nombre;
	}

	public void setRut(String rut) {
		this.rut = rut;
	}

	public void setFechaDeNacimiento(String fechaDeNacimiento) {
		this.fechaDeNacimiento = fechaDeNacimiento;
	}

	public void setPlanetaDestinoCC(String planetaDestinoCC) {
		this.planetaDestinoCC = planetaDestinoCC;
	}
	
	
	

}//Fin class clienteCriminal

public class vehiculo {
	
	private int idVehiculo;
	private String tipo;
	private int uaAcumulada;
	private String autonomia;
	
	public vehiculo(int idVehiculo, String tipo, int uaAcumulada, String autonomia) {
		super();
		this.idVehiculo = idVehiculo;
		this.tipo = tipo;
		this.uaAcumulada = uaAcumulada;
		this.autonomia = autonomia;
	}

	public int getIdVehiculo() {
		return idVehiculo;
	}

	public String getTipo() {
		return tipo;
	}

	public int getUaAcumulada() {
		return uaAcumulada;
	}

	public String getAutonomia() {
		return autonomia;
	}

	public void setIdVehiculo(int idVehiculo) {
		this.idVehiculo = idVehiculo;
	}

	public void setTipo(String tipo) {
		this.tipo = tipo;
	}

	public void setUaAcumulada(int uaAcumulada) {
		this.uaAcumulada = uaAcumulada;
	}

	public void setAutonomia(String autonomia) {
		this.autonomia = autonomia;
	}
	
	

}//Fin class Vehiculo

public class planeta {
	
	private int idPlaneta;
	private String galaxia;
	private int distanciaUA;
	private int categoria;
	private int cupoDisponible;
	
	public planeta(int idPlaneta, String galaxia, int distanciaUA, int categoria, int cupoDisponible) {
		super();
		this.idPlaneta = idPlaneta;
		this.galaxia = galaxia;
		this.distanciaUA = distanciaUA;
		this.categoria = categoria;
		this.cupoDisponible = cupoDisponible;
	}

	public int getIdPlaneta() {
		return idPlaneta;
	}

	public String getGalaxia() {
		return galaxia;
	}

	public int getDistanciaUA() {
		return distanciaUA;
	}

	public int getCategoria() {
		return categoria;
	}

	public int getCupoDisponible() {
		return cupoDisponible;
	}

	public void setIdPlaneta(int idPlaneta) {
		this.idPlaneta = idPlaneta;
	}

	public void setGalaxia(String galaxia) {
		this.galaxia = galaxia;
	}

	public void setDistanciaUA(int distanciaUA) {
		this.distanciaUA = distanciaUA;
	}

	public void setCategoria(int categoria) {
		this.categoria = categoria;
	}

	public void setCupoDisponible(int cupoDisponible) {
		this.cupoDisponible = cupoDisponible;
	}
	
	
	
	

}/*Fin class planeta*/

public class viaje {
	
	private int combustible;
	private Vehiculo vehiculo;
	private int tripulacion;
	private int distancia;
	public viaje(int combustible, Vehiculo vehiculo, int tripulacion, int distancia) {
		super();
		this.combustible = combustible;
		this.vehiculo = vehiculo;
		this.tripulacion = tripulacion;
		this.distancia = distancia;
	}
	public int getCombustible() {
		return combustible;
	}
	public Vehiculo getVehiculo() {
		return vehiculo;
	}
	public int getTripulacion() {
		return tripulacion;
	}
	public int getDistancia() {
		return distancia;
	}
	public void setCombustible(int combustible) {
		this.combustible = combustible;
	}
	public void setVehiculo(Vehiculo vehiculo) {
		this.vehiculo = vehiculo;
	}
	public void setTripulacion(int tripulacion) {
		this.tripulacion = tripulacion;
	}
	public void setDistancia(int distancia) {
		this.distancia = distancia;
	}
	
	

}//Fin class viaje

public class comprobante {
	
	private String planetaDestino;
	private String fechaViaje;
	private String fechaComprobante;
	private String vehiculo;
	public comprobante(String planetaDestino, String fechaViaje, String fechaComprobante, String vehiculo) {
		super();
		this.planetaDestino = planetaDestino;
		this.fechaViaje = fechaViaje;
		this.fechaComprobante = fechaComprobante;
		this.vehiculo = vehiculo;
	}
	public String getPlanetaDestino() {
		return planetaDestino;
	}
	public String getFechaViaje() {
		return fechaViaje;
	}
	public String getFechaComprobante() {
		return fechaComprobante;
	}
	public String getVehiculo() {
		return vehiculo;
	}
	public void setPlanetaDestino(String planetaDestino) {
		this.planetaDestino = planetaDestino;
	}
	public void setFechaViaje(String fechaViaje) {
		this.fechaViaje = fechaViaje;
	}
	public void setFechaComprobante(String fechaComprobante) {
		this.fechaComprobante = fechaComprobante;
	}
	public void setVehiculo(String vehiculo) {
		this.vehiculo = vehiculo;
	}
	

}//Fin class comprobante

public class main {

	public static void main(String[] args) {
