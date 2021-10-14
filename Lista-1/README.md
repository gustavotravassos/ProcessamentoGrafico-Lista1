## Processamento Gráfico - Lista 1

# Questão 1 - O que é a GLSL? Quais os dois tipos de shaders são obrigatórios no pipeline programávelda versão atual que trabalhamos em aula e o que eles processam?

Linguagem de Shaders baseada em C. 
VertexShader (Posições) e FragmentShader (Cores e elementos gráficos).

# Questão 2 - O que são primitivas gráficas? Como fazemos o armazenamento dos vértices na OpenGL?

Elementos básicos dos gráficos/desenhos a partir dos quais construímos elementos mais complexos, fazemos seu armazenamento via SR, que é um sistema de referência próprio do sistema que se subdivide em vários casos (SRU, SRD, SRO, SRN).

# Questão 3 - Explique o que é VBO, VAO e EBO, e como se relacionam (se achar mais fácil, pode fazer um gráfico representando a relação entre eles). 

VBO significa Vertex Buffer Object, VAO significa Vertex Array Object e EBO significa Element Buffer Object.

# Questão 4 - Considerando o seguinte triângulo abaixo, formado pelos vértices P1, P2 e P3, respectivamente com as cores vermelho, verde e azul. a. Descreva uma possível configuração dos buffers (VBO, VAO e EBO) para representá-lo. b. Como estes atributos seriam identificados no vertex shader?
