import Foundation
print("\n¡Bienvenido al curso de FÍSICA! \n")
print("El dia de hoy estudiaremos y calcularemos la VELOCIDAD...\n")
print("La velocidad es una magnitud que indica el cambio de posición de un cuerpo respecto al tiempo. En física, la velocidad se define como el cociente entre el desplazamiento y el intervalo de tiempo entre la posición inicial y la final.")
// Función para calcular la velocidad
func calcularVelocidad(distancia: Double, tiempo: Double) -> Double {
    return distancia / tiempo
}
// Solicitar al usuario la distancia y el tiempo
print("\nIngrese la distancia (en metros): ", terminator: "")
if let distanciaString = readLine(), let distancia = Double(distanciaString) {
    print("Ingrese el tiempo (en segundos): ", terminator: "")
    if let tiempoString = readLine(), let tiempo = Double(tiempoString) {
        // Calcular la velocidad
        let velocidad = calcularVelocidad(distancia: distancia, tiempo: tiempo)
        print("La velocidad es de \(velocidad) metros por segundo.")
    } else {
        print("Tiempo inválido. Ingrese un valor numérico válido.")
    }
} else {
    print("Distancia inválida. Ingrese un valor numérico válido.")
}
print("\nCon eso se calcula la velocidad de cualquier cosa,ya sea de un vehículo,de un avión e inclusive de un objeto cualquiera.")
print("\nLa importamcia de la velocidad es la siguiente:")
print("\nCuando necesitamos información sobre la dirección y el sentido del movimiento, así como su rapidez recurrimos a la velocidad.")
print("\nNos permite llevar a cabo acciones motrices en el menor tiempo posible. ...")
print("\nDe manera genérica, podemos decir, que la velocidad aumenta en función de la fuerza")
print("\nHasta aquí llegó el curso de hoy...")
print("\nNos vemos mañana en el próximo curso")
print("¡Hasta luego,adiós!")
