# Integra-o_sistemas
**DESAFIO: Integração de sistemas**

Você foi contratado(a) para construir um programa utilitário para facilitar a integração entre uma
plataforma de vídeo (que está sendo utilizada para armazenar vídeo aulas) e uma área de membros
onde os alunos estudam os cursos.

Os vídeos são exportados pela plataforma de vídeo no formato CSV. Cada registro CSV contém o id
da aula, o título da aula, bem como sua duração em segundos. O título da aula começa com uma
numeração, que indica o capítulo e a aula neste capítulo (você pode considerar que essa numeração e o
espaço antes do início do título sempre vai ter 6 caracteres, conforme exemplo abaixo).

Você deverá construir uma função para converter os dados CSV para o formato JSON, pois este JSON
será utilizado para alimentar uma API web da plataforma de ensino.

Você deverá fazer alguns ajustes nos dados:
- A numeração da aula não deve aparecer no título do resultado final.
- O final ".mp4" dos títulos deve ser removido.
  
Sua função deve receber uma lista de strings no formato CSV, e sua função deve retornar um string
com os dados no formato JSON, como mostrado no exemplo a seguir.
Sua função deve obedecer a assinatura especificada no final deste documento.
Você deve gerar o JSON programaticamente, sem utilizar uma biblioteca externa de JSON.
Requisito não eliminatório: você deve retornar o JSON formatado com as devidas quebras de linha e
indentação.

Exemplo:

<img width="674" height="297" alt="image" src="https://github.com/user-attachments/assets/9df48024-d6fd-4765-a9b4-9d4a28aaadc5" />
<img width="422" height="646" alt="image" src="https://github.com/user-attachments/assets/1d935165-e606-4867-a854-b03fd4e51c8d" />
<img width="433" height="301" alt="image" src="https://github.com/user-attachments/assets/659f70ac-940e-4840-9988-ea4b81bf623c" />
