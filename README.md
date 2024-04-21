camel_case = input("ingrese su nombre de variable en CamelCase: ")

snake_case = ""


for i in range (len(camel_case)):

    if camel_case[i].isupper():

        snake_case +="_" + camel_case [i].lower() 
    else:
 
        snake_case += camel_case [i]

print ("El nombre de la variable en Snake_case es: " , snake_case)
