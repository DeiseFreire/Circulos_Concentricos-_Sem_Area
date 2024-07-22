## Calculo da área limitada pelas equações x2 + y2 = 4 e x2 + y2 = 1 utilizando coordenadas polares 

As equações representam dois círculos centrados na origem com raios de 2 e 1 unidade respectivamente. Em coordenadas polares, x² + y² = r², então ambas as equações se traduzem em círculos definidos por:

1. r² = 4 (raio 2)
2. r² = 1 (raio 1)

No entanto, a área que queremos encontrar não é toda a área delimitada por estes círculos. Não há sobreposição entre esses círculos porque 2 > 1. Portanto, estamos essencialmente encontrando o espaço vazio entre os dois círculos.

Veja como calcular a área usando coordenadas polares:

1. Montaremos uma integral dupla onde a primeira integral representa a variação em teta (ângulo) e a segunda integral representa a variação no raio.
2. Como estamos lidando com a área entre dois círculos, precisaremos subtrair a área do círculo menor (raio 1) da área do círculo maior (raio 2).

**Etapa 1: Configurando a integral dupla**

Sabemos que o elemento de área em coordenadas polares é dA = 1/2 * r * dr * dθ. Aqui, dθ representa a mudança no ângulo e dr representa a mudança no raio.

O círculo maior vai de um raio de 0 (origem) a um raio de 2. O círculo menor vai de 0 a 1. Teta (ângulo) vai de 0 a 2π para um círculo completo (embora dependendo do quadrante, possamos precisar para ajustar o intervalo).

Portanto, a integral dupla para encontrar a área total delimitada por ambos os círculos é:

A_total = ∫(0 a 2π) ∫(0 a 2) (1/2 * r * dr * dθ)

**Etapa 2: Subtraindo a área do círculo menor**

Para encontrar a área entre os círculos, subtraímos a área do círculo menor da área total:

Área_entre_círculos = A_total - Área_menor_círculo

Área_círculo_menor = ∫(0 a 2π) ∫(0 a 1) (1/2 * r * dr * dθ)

**Etapa 3: Resolva as integrais**

Ambas as integrais seguem o mesmo padrão:

∫(a a b) (1/2 * r^2 * dr) = (1/6) * r^3 avaliado de a a b

Portanto:

A_total = (1/6) * (2 ^ 3) * ∫ (0 a 2π) dθ = (4/3) * 2π

Área_círculo_menor = (1/6) * (1 ^ 3) * ∫ (0 a 2π) dθ = (1/3) * 2π

**Etapa 4: Encontre a área entre os círculos**

Área_entre_círculos = (4/3) * 2π - (1/3) * 2π = (3/3) * 2π = 2π

Portanto, a área delimitada entre os círculos x² + y² = 4 e x² + y² = 1 usando coordenadas polares é de 2π unidades quadradas.
