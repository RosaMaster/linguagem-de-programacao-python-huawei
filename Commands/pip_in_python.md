### **PIP**

#### **O que é pip em python?**
PIP é um gerenciador de pacotes para Python. Ele permite que você instale e gerencie bibliotecas e dependências que não fazem parte da biblioteca padrão do Python. Com o PIP, você pode facilmente instalar pacotes de terceiros a partir do Python Package Index (PyPI).

#### **Comandos**

| **Comando**                       | **Exemplo**                     | **Descrição**                                                                   |
| --------------------------------- | ------------------------------- | ------------------------------------------------------------------------------- |
| `pip install <lib-name>`          | pip install numpy               | é usado para instalar pacotes Python                                            |
| `pip install <lib-name==version>` | pip install numpy==1.21.0       | é usado para instalar pacotes com versão específica                             |
| `pip list`                        | pip list                        | isso mostrará uma lista de pacotes instalados e suas respectivas versões        |
| `pip show <lib-name>`             | pip show numpy                  | exibe informações detalhadas sobre um pacote instalado                          |
| `pip uninstall <lib-name>`        | pip uninstall numpy             | é usado para desinstalar pacotes Python                                         |
| `pip freeze > requirements.txt`   | pip freeze > requirements.txt   | gera uma lista de pacotes instalados e suas versões no formato requirements.txt |
| `pip install -r requirements.txt` | pip install -r requirements.txt | instala todos os pacotes listados no arquivo requirements.txt                   |
| `python --version`                | python --version                | exibe a versão do Python instalada no sistema                                   |

#### **Exemplos Outputs**

<br>

`pip list`
~~~Python
Package                   Version
------------------------- --------------
networkx                  3.3
notebook                  7.1.2
numpy                     2.0.0
~~~
