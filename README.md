#encoding: UTF-8


d= {"Aguascalientes":"Aguascalientes",
"Baja California": "Mexicali",
"Baja California Sur": "La Paz",
"Campeche": "San Francisco de Campeche",
"Chihuahua": "Chihuahua",
"Chiapas": "Tuxtla Gutiérrez",
"Coahuila": "Saltillo",
"Colima": "Colima",
"Durango": "Victoria de Durango",
"Guanajuato": "Guanajuato",
"Guerrero": "Chilpancingo de los Bravo",
"Hidalgo": "Pachuca de Soto",
"Jalisco": "Guadalajara",
"México": "Toluca de Lerdo",
"Michoacán": "Morelia",
"Morelos": "Cuernavaca",
"Nayarit": "Tepic",
"Nuevo León": "Monterrey",
"Oaxaca": "Oaxaca de Juárez",
"Puebla": "Puebla de Zaragoza",
"Querétaro": "Santiago de Querétaro",
"Quintana Roo": "Chetumal",
"San Luis Potosí": "San Luis Potosí",
"Sinaloa": "Culiacán Rosales",
"Sonora": "Hermosillo",
"Tabasco": "Villahermosa",
"Tamaulipas": "Ciudad Victoria",
"Tlaxcala": "Tlaxcala de Xicohténcatl",
"Veracruz": "Xalapa-Enríquez",
"Yucatán": "Mérida",
"Zacatecas": "Zacatecas"}
print("Bienvenido")

for i in d:
    print(i)
    solucion=d[i]
    intento=raw_input("Cuál es la capital del estado anterior")
    if intento==solucion:
        print(":V")
    else:

        print(";-(")

