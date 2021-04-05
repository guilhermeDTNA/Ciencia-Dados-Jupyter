# Ciência de Dados com Jupyter

<h3>Trabalho desenvolvido na disciplina de Tópicos Especiais em Sistemas de Informação I</h3>

Para executá-lo, voc necessita ter a versão 3.6 do Python instalado, juntamente com o Jupyter, o qual pode ser instalado pelo seguinte comando:

```console

$ sudo apt install jupyter-notebook

```

Após isso, altere a versão default do seu Python para a mencionada anteriormente, se já não o tiver feito:

```console

$ sudo update-alternatives --install /usr/bin/python python /usr/bin/python3 10

```
Agora é só instalar as bibliotecas utilizadas no projeto com o gerenciador pip3:

```console

$ sudo pip3 install pandas && sudo pip3 install matplotlib

```

Por último, execute-o com: 

```console

$ jupyter-notebook 

```