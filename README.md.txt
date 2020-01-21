Tablero[][];

Tanques()
{
	vida(numero de impactos);
	posicionX;
posicionY;
retraso(Recarga de cañon);
posicionCanhon;
horaUltimoDisparo;
imagenTanque;

mueveDerecha();
mueveIzq();
mueveArriba();
mueveAbajo();

/*
0 - Derecha
1 - Izquierda
2 - Arriba
3 - Abajo
*/
mueve(int direccion);
{
	switch(direccion)
{
	case ‘letra’:
		mueveDireccion();
}
}

disparo()
{
	if(horaActual-horaUltimoDisparo>=retraso)
{
	Posicion tank+1
	//Cosas
}
}
}
Jugador()
{
	nombre;
	puntuacion;
	tanque;
}
Bala()
{
	posicionX;
	posicionY;
	direccion(?);
}

Mecanicas
●	+1 puntuacion cuando matas un tanque
●	-1 puntuacion cuando muere tu tanque.
●	colision de tanques resta vida a ambos.
●	movimiento tanque WASD
●	movimiento cañon flechas
