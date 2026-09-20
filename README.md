# Consumo-agua

Objetivo: Calcular o consumo de água de uma determinada cidade para conscientização dos moradores.

Linguagem usada foi a Pyhton.

Segue abaixo a programação em Python com as informações para realizar o calculo do consumo, para executar a programação será necessário copiar o código e executar em um leitor Python.

tipo_imovel = input("Digite o tipo de Imovel:")
consumo = float(input("Digite o consumo mensal de agua em M³:"))
if tipo_imovel == "Comercial":
    print("Comercial Aplicada - Consulte Plano Corporativo.")
elif tipo_imovel == "Apartamento" and consumo <10:
    print("Consumo Econômico – Excelente Controle de Água!")
elif (tipo_imovel == "Apartamento" or tipo_imovel == "Casa") and consumo <=25:
    print("Consumo Moderado – Dentro do Padrão Residencial.")
else:
    print("Consumo Excessivo – Adote Medidas de Economia e Verifique Vazamentos.")


![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Energia](https://img.shields.io/badge/Energia-Eficiente-brightgreen?style=for-the-badge&logo=leaf&logoColor=white)
![Calculadora](https://img.shields.io/badge/Projeto-Calculadora-orange?style=for-the-badge&logo=calculator&logoColor=white)
