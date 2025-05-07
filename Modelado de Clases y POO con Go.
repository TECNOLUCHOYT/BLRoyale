✅ PlantUML — Diagrama de Clases Inicial (POO estilo Go)
- plantuml
- Copiar
- Editar
@startuml

title Sistema de Turnos Médicos - Modelo Inicial en Go

' Interfaces
interface Notificador {
    +Notificar(mensaje: string): error
}

' Structs principales
class Usuario {
    +ID: int
    +Nombre: string
    +Email: string
}

class Paciente {
    +DNI: string
    +Telefono: string
    +Usuario: Usuario
    +SolicitarTurno(medicoID: int, fecha: string): Turno
}

class Medico {
    +Matricula: string
    +Especialidad: string
    +Usuario: Usuario
    +VerTurnos(): []Turno
}

class Turno {
    +ID: int
    +Fecha: string
    +Estado: string
    +PacienteID: int
    +MedicoID: int
    +Cancelar(): error
}

class HistoriaClinica {
    +ID: int
    +PacienteID: int
    +Notas: []string
    +AgregarNota(nota: string): error
}

class TurnoService {
    +AsignarTurno(pacienteID: int, medicoID: int, fecha: string): Turno
    +CancelarTurno(turnoID: int): error
}

' Relaciones
Paciente --> Usuario : has a >
Medico --> Usuario : has a >
Paciente --> Turno : solicita >
Medico --> Turno : atiende >
Turno --> HistoriaClinica : registra >
TurnoService --> Turno : gestiona >

Paciente ..|> Notificador
Medico ..|> Notificador

@enduml
🧠 Diseño orientado a Go:
Elemento Go	Representación en el diagrama
struct	Clases como Paciente, Medico, Turno, etc.
Composición	Usuario embebido en Paciente y Medico
Interfaces	Notificador con método Notificar()
Métodos	Asociados a structs (como Cancelar(), SolicitarTurno(). 
