# Editor de Texto via console usando .NET e C#

- Opções: Criar arquivo, Salvar arquivo, Ler Arquivo, futuramente adicionar mais funções
- Métodos: Foi utilizado um Switch para as opções do menu; para escrever os textos foi utilizado o Do/While
juntamente com o Console.ReadLine() e Environment.NewLine enquanto a tecla Esc não fosse digitado e para isso
foi utilizado os métodos Console.ReadKey().Key e o ConsoleKey.Escape;
Para salvar o arquivo foi criado utilizado o método StreamWriter(path) para ler o caminho do arquivo e o file.write(text)
para escrever no arquivo o texto digitado; Por fim para abrir o arquivo foi utilizado o StreamReader(path) juntamente com
o ReadToEnd() para ler todo o arquivo; Para isso foi necessário usar o using dentro dos métodos.
