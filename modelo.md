equipo
    nombre:text
    logo: text
    estado:boolean

jugador
    nombre:text:
    edad:number
    apodo:text
    foto:text
    estado:boolean
    equipo:idEquipo

partida
    jugadorA:idJugador
    jugadorB:idJugador
    fecha:date
    sitio:text:
    ganador:idJugador

sitio
    nombre:text
    direccion_text
    estado:boolean
    foto:text

