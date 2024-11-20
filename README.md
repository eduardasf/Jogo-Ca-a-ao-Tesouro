## Seja Bem-Vindo!

# Tommy e a Floresta dos Desafios

Este repositório contém toda a documentação do jogo Tommy e a Floresta dos Desafios, desenvolvido como projeto final da disciplina de Computabilidade e Complexidade de Algoritmos.

### 👨‍💻Integrantes do trabalho:
- Eduarda Fernandes - 29204356 - [GitHub](https://github.com/eduardasf)
- Davi Santos - 31075550 - [GitHub](https://github.com/Davi140903)

### Links do Trabalho

🔗[Checklist para o Projeto de Algoritmo](https://docs.google.com/document/d/1Srs0VaEi86X3VZb1j1cGalZr3vO_3jp-KXp8-Y3Nx9Y/edit?usp=sharing)

🔗[Link do Jogo - Scratch](https://docs.google.com/document/d/1Srs0VaEi86X3VZb1j1cGalZr3vO_3jp-KXp8-Y3Nx9Y/edit?usp=sharing)

🔗[Video do jogo - Youtube](https://docs.google.com/document/d/1Srs0VaEi86X3VZb1j1cGalZr3vO_3jp-KXp8-Y3Nx9Y/edit?usp=sharing)

## Vamos Começar!
### O que é um jogo de Caça ao Tesouro?
O Caça ao tesouro em si é um jogo de enigmas em que os participantes devem resolver para encontrar a recompensa final. A cada mistério resolvido os participantes terão uma nova pista de onde está escondido o próximo enigma, para assim conseguir chegar ao destino final, o prêmio.

### 🕹️ Sobre o Jogo
Tommy e a Floresta dos Desafios é um mini-jogo de caça ao tesouro que conta a história de Tommy, um gato que parte em busca de seu amigo favorito, chamado Jerryme.

Tudo começa quando Tommy percebe que seu amigo desapareceu de casa. Jerryme foi sequestrado por um ogro travesso, que o escondeu em uma floresta cheia de mistérios. O ogro, que na verdade só queria alguém para brincar, desafia Tommy a resgatar o amigo. Para isso, Tommy terá que entrar na floresta e encontrar as três chaves deixadas pelo ogro para abrir o baú no final do mapa e libertar Jerryme do calabouço.

A missão do jogador é ajudar Tommy a encontrar seu melhor amigo, resolvendo os enigmas espalhados pela floresta para obter as chaves e, no fim, conseguir libertá-lo. 

### 💻Tecnologias Utilizadas no Desenvolvimento
- Scratch

### 💡 Inspiração Para o Projeto
O jogo foi inspirado em projetos simples de caça ao tesouro disponíveis na plataforma Scratch. Alguns exemplos utilizados como referência incluem:
- [Caça ao Tesouro — Autômatos de Estados Finitos](https://scratch.mit.edu/projects/570436056/) - desenvolvedor: mfopina
- [Labirinto: Caça ao Tesouro](https://scratch.mit.edu/projects/833716412/) - desenvolvedor: GdeuPegaramMeuNome
- [Caça ao tesouro](https://scratch.mit.edu/projects/402888020/) - desenvolvedor: anedebald

### 🧩 Problema a Ser Resolvido:
O problema que queremos resolver é: "Como criar um algoritmo de caça ao tesouro no Scratch que inclua dicas baseadas na proximidade entre o jogador e o tesouro"

Para solucionar este problema, utilizamos como base o modelo matemático da distância euclidiana. Mas o que é esse modelo?

De acordo com a Wikipedia, a distância euclidiana é a distância entre dois pontos em um espaço, que pode ser determinada pela aplicação repetida do teorema de Pitágoras. Ao aplicar essa fórmula de distância, o espaço euclidiano torna-se um espaço métrico.

Existem várias maneiras de calcular a distância entre pontos, dependendo da dimensão do espaço. Algumas delas são:
- Distância unidimensional
- Distância bidimensional
- Distância tridimensional
- Distância n-dimensional
  
Neste caso, utilizamos a distância bidimensional, que é calculada da seguinte forma:
![image](https://github.com/user-attachments/assets/80203912-d457-45c9-9290-3de38e5b4955)

### 🎯Regras (Jogabilidade)

Regras:

- O jogador começa o jogo com 3 vidas.
- A cada resposta errada ou ao não conseguir encontrar o baú, o jogador perde uma vida.
- Se todas as 3 vidas forem perdidas, o jogo termina e o jogador será redirecionado para o início.
  
### 📈Desempenho do Jogo
Para testar a usabilidade e o desempenho do jogo, realizamos um questionário com 6 perguntas para um total de 5 pessoas. Elas responderam às perguntas com sim/não. Com isso, obtivemos vários resultados e montamos uma tabela para facilitar a visualização.

Questionário realizado:
- O personagem se move quando você pressiona as teclas?
- O objetivo do jogo está claro para o jogador?
- É possível iniciar o jogo ao clicar na bandeira verde?
- O fundo ou cenário muda em algum momento, se necessário?
- O placar aumenta ou diminui corretamente?
- O jogo termina quando o jogador perde ou ganha?

Resultado de cada pergunta:
| Pergunta                                               | Sim | Não |
|--------------------------------------------------------|-----|-----|
| O personagem se move quando você pressiona as teclas?  | 5   | 0   |
| O objetivo do jogo está claro para o jogador?          | 5   | 0   |
| É possível iniciar o jogo ao clicar na bandeira verde? | 5   | 0   |
| O fundo ou cenário muda em algum momento?              | 4   | 1   |
| O placar aumenta ou diminui corretamente?              | 5   | 0   |
| O jogo termina quando o jogador perde ou ganha?        | 5   | 0   |

### ✨Conclusão

Criar este mini-jogo do zero foi uma experiência incrível! Cada etapa, desde o estudo inicial até superar os desafios do desenvolvimento, foi cheia de aprendizados e superações. Foi muito legal ver o resultado final tomando forma e poder compartilhá-lo com várias pessoas para testar e receber suas impressões.

Quando analisamos os resultados dos questionários, ficou claro que o jogo conseguiu cumprir o que foi planejado desde o início. Saber que ele proporcionou a experiência esperada e ver as reações positivas das pessoas foi muito gratificante. Além disso, o feedback recebido trouxe novas ideias e motivação para seguir melhorando. Foi uma jornada desafiadora, mas muito recompensadora!

### 📚Referências para a pesquisa:
- [JOGO DIDÁTICO: CAÇA TESOURO GEOGRÁFICO](https://www.falaprofessor2023.agb.org.br/resources/anais/9/fp2023/1693513698_ARQUIVO_41e17d5f72c272576d276d118152fb95.pdf) - Altores: Jeane Araújo - Vitória Santos de Jesus - Maísa Barbosa Caldas - Bruno Rodrigues da Silveira
- [Distância euclidiana](https://pt.wikipedia.org/wiki/Dist%C3%A2ncia_euclidiana) - Wikipedia
