# DesignPattern

Material con fines educativos sin ánimo de lucro integrantes.
Sebastian Amilkar
Milmax 
-----------------------------------------------------------------------------------------------------------------------
****¿Que significa que mi sistema sea modular y tenga un bajo acople?
-------------------------------------------------------------------------------------------------------------------------
Significa que tengo un sistema  donde las diferentes partes no poseen una alta dependencia entre ellas, y por el contrario, 
su funcionalidad e implementación es distribuida y/o desarrollada bajo un patrón de baja dependencia entre componentes. Adicionalmente,
poseen un desarrollo que define las tareas propias de un módulo, las cuales posean cohesion con la implementación
de ese módulo.

-----------------------------------------------------------------------------------------------------------------------
****¿Por qué quiero que un módulo en mi sistema tenga alta cohesión?
------------------------------------------------------------------------------------------------------------------------
Porque esto me permite reducir el acople del sistema en general, disminuyendo los errores y el número de cambios que deba 
realizar en la aplicación.

-----------------------------------------------------------------------------------------------------------------------
****¿Que es un monolito?
------------------------------------------------------------------------------------------------------------------------
Es un desarrollo con todas las funcionalidades en un solo módulo. Representa dificultad en el mantenimiento y problemas en
escabilidad del servicio y/o sistema en general.

------------------------------------------------------------------------------------------------------------------------
****Por qué no quiero diseñar mi sistema como un monolito?
------------------------------------------------------------------------------------------------------------------------
Porque dificulta el mantenimiento y la escalabilidad de la aplicación además de agregar mayor complejidad dificil de mantener
y dar soporte a medida que la aplicación crezca. Lo mejor es plantear un desarrollo de bajo acople y modular.
