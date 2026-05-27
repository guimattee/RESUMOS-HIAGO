Separado em 3 categorias com 23 padrões:
* **Criacionais;** (5)
* **Estruturais;** (7)
* **Comportamentais;** (11)
# Criacionais:
* #### **Factory:**
Ao inves de criar varias vezes uma funcao, cria uma "fabrica"
	EX: passar as infromacoes que precisa e o factory traz o resultado em cima dessas informacoes
(centraliza o trabalho para nao repetir)

* #### **Singleton:**
Ter apenas um rodando no código inteiro

# Estruturais:
* #### **Adapter:**
Traduz a comunicação, permitindo que interfaces incompativeis tralhem juntas
	EX: traduz de reais para centavos

* ### **Facade**:
Esconde interfaces complexas por trás de metodos simples
	EX: ao finalizar uma compra, chama apenas o finalizarCompra(), que consulta estoque por trás dos panos

* ### Composite:
Hierarquia em árvores
	EX: dentro de uma pasta, ter arquivos e outra pasta que tem mais arquivos dentro...

# Comportamentais:
* ### Observer:
Fica observando um objeto, quando o objeto muda, avisa outros sistemas
	EX: quando adiciona algo no carrinho, ele avisa o estoque

* ### Strategy:
Permite trocar a regra durante a execução do programa
	EX: calcular a mudanca do valor do frete da transportadora que foi trocada