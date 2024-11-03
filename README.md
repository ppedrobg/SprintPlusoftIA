ChallengePlusoft
Autocrítica e Reflexão
Durante o desenvolvimento, enfrentamos alguns desafios, como a incompatibilidade de certas imagens para o treinamento, o que tornou o processo repetitivo em alguns momentos. Além disso, a documentação do YOLOv8 se concentrou principalmente nas configurações visuais, e sentimos falta de mais orientações para análises avançadas dos dados. Sentimos que seria necessário para as etapas, algo mais sofisticado, pois seria de grande bom gosto conseguir expandir a forma em que pensamos no programa e como iria ser transmitida essa proposta para a forma real que foi concretizada a solução final.

Por passar e se desenvolver, sentimos que ficou limitado a forma de resolução e gostaríamos de ter efetivado algo mais real, conseguindo integrar a outros serviços que para o desenvolvimento e com a integração poderia se tornar algo até mais interessante de certa forma.

Mas nos sentimos realizados como a forma que foi discorrida com o passar do tempo, com muito prestígio e trabalho em equipe, nosso time conseguiu finalizar algo que se compare e que segue uma linha de um grande futuro.

Ademais, sem dificuldades não seria possível chegar aonde chegamos e com desafios que conseguimos solucionar, sentimos um grande prazer por ter passado em todas essas fases.

Desenvolvimento do Projeto
O projeto foi desenvolvido com o uso do Roboflow para anotar e processar imagens, visando a criação de um provador digital, uma inovação que acreditamos poder beneficiar significativamente o mercado de moda. Nossa equipe identificou a oportunidade de aprimorar a experiência de compra de roupas online, permitindo que os clientes "experimentem" as peças virtualmente. A proposta foi conduzida com o objetivo de criar um sistema eficiente, de fácil uso e personalizável.

O processo inicial envolveu a coleta de um vasto conjunto de dados visuais, baixando mais de 300 imagens de diversas fontes. Optamos pelo Roboflow devido à sua interface intuitiva, que facilitou o upload das imagens e o processo de anotação. Embora a marcação individual de cada imagem e a criação de suas respectivas classes tenham sido demoradas, o Roboflow otimizou etapas cruciais, como a separação das imagens em conjuntos de treino, teste e validação, para o treinamento do nosso modelo.

Após a preparação do dataset, desenvolvemos um código para consumir a API do Roboflow e carregar as imagens anotadas de maneira organizada. Isso permitiu que nosso algoritmo processasse os dados e passasse por diversas etapas de aprendizado. Utilizando métricas como F1-score, precisão e recall, avaliamos e monitoramos a eficácia do modelo, obtendo feedback constante sobre o desempenho e ajustes necessários.

Principais Ferramentas e Recursos
Utilizamos uma série de ferramentas especializadas para garantir a qualidade e o desempenho do modelo, incluindo:

Roboflow: Para o gerenciamento e pré-processamento dos dados de imagem.
OpenCV (cv2): Uma biblioteca robusta para processamento de imagem e visão computacional.
Google Colab Patches: Para integração prática com OpenCV dentro do ambiente Google Colab.
Ultralytics (YOLOv8): Um modelo avançado para detecção de objetos e classificação de imagens.
PyTorch (torch): Framework de aprendizado profundo, permitindo treinamento e construção de modelos com uso de GPU.
Resultados e Propostas de Expansão
Ao final, estruturamos o código por sessões para um entendimento mais claro de cada etapa do projeto, como anotação, treinamento e validação dos dados. O sistema está agora preparado para processar peças de roupas de clientes que desejam usar a tecnologia do provador virtual. Com isso, o modelo se adapta rapidamente e diferencia de forma eficaz cada peça, oferecendo visualizações otimizadas de frente e verso. Isso não apenas economiza tempo e trabalho, mas também proporciona uma experiência personalizada, atendendo às necessidades específicas de clientes com e-commerces e lojas físicas que visam expandir para o mercado digital.

Para aprimorar o projeto, sugerimos as seguintes adições:

Aprimorar a Interface de Anotação: Poderíamos adicionar uma etapa intermediária para agrupar e rotular automaticamente as imagens, reduzindo o esforço de marcação manual.
Integração com Modelos de Realidade Aumentada (AR): A incorporação de uma camada de realidade aumentada para permitir que o usuário visualize as roupas em modelos 3D aumentaria ainda mais o valor da aplicação.
Feedback em Tempo Real: A adição de um sistema de feedback visual durante a detecção, para que os usuários vejam os pontos de ajuste, como posição e escala das roupas, diretamente na interface.
Automação de Ajuste de Tamanhos: Um recurso para ajustar automaticamente o tamanho das peças com base no tipo de corpo, aprimorando a personalização.
Essas adições poderiam elevar ainda mais a proposta, oferecendo uma experiência de provador virtual dinâmica e envolvente, além de simplificar o processo de desenvolvimento.

E levar adiante as técnicas usadas, com mais maturidade e entendimento sobre todas as etapas concluídas.

Sistema de Recomendação Personalizada: O sistema de recomendação será alimentado por algoritmos de IA generativa para analisar padrões de comportamento. Através do treinamento e avaliação contínuos, o sistema recomendará roupas adequadas para cada cliente, assim facilitando e aumentando a chance do cliente efetuar a compra sem passar por insegurança de não saber como a peça de roupa irá se enquadrar em seu físico.
Essas atualizações no projeto garantem uma experiência de compra online mais interativa, personalizada e eficiente, permitindo que os usuários se imaginem com as roupas que escolheram de diferentes ângulos.

