# Práticas da Disciplina de Computação Gráfica

Este repositório contém as implementações desenvolvidas para a disciplina de **Computação Gráfica**, ministrada no curso de Engenharia de Computação na UFRN.  
As práticas foram realizadas em **C** utilizando **OpenGL** (FreeGLUT) e abrangem desde conceitos básicos de desenho de primitivas até modelagem e transformação de objetos 3D.

## 📋 Conteúdo

O projeto está organizado conforme os tópicos abordados na disciplina:

1. **Compilação dos Projetos**
   - Makefile base para compilação no Windows com MinGW.
   - Linkagem automática das bibliotecas `freeglut`, `opengl32`, `glu32`.

2. **Curvas no Plano**
   - Splines NURBS interativas.
   - Comparação entre vetores de nós uniforme, uniforme aberto e não-uniforme.
   - Diferenças entre curvas Bézier e NURBS de mesma ordem.

3. **Desenhando Linhas e Pontos**
   - Desenho de um quadrado simples (`quadrado.c`).
   - Algoritmo de Bresenham para linhas.
   - Algoritmo de Bresenham para circunferências.

4. **Modelagem de Sólidos**
   - Modelagem de um avião a jato (`superjato.c`).
   - Adição de logotipo personalizado na asa.

5. **Modelos de Iluminação e Sombreamento**

6. **Preenchimento de Regiões**
   - Seleção com e sem buffer.
   - Preenchimento de áreas.

7. **Projeções Geométricas**
   - Tipos de projeções ortogonais e em perspectiva.

8. **Superfícies no Espaço**

9. **Transformações Geométricas**
   - Braço robótico 2D e 3D com garra controlável.

## 🛠️ Tecnologias Utilizadas
- **Linguagem:** C
- **Bibliotecas:** OpenGL, FreeGLUT, GLU
- **Compilador:** MinGW (Windows)
- **Sistema de Construção:** Makefile

## 🚀 Como Executar

1. **Instale o MinGW** e as bibliotecas OpenGL/FreeGLUT.
2. **Clone o repositório:**
   ```bash
   git clone https://github.com/SEU_USUARIO/SEU_REPOSITORIO.git
   cd SEU_REPOSITORIO

  3.Edite o Makefile alterando a variável EXEC para o nome do programa desejado (sem extensão .c).
 
4. Compile:
   ```bash
   make
   ```
5. Execute:
    ```bash
   ./NOME_DO_EXECUTAVEL.exe
    ```
6. Para limpar os binários gerados:
   ```bash
   make clean
   ```

