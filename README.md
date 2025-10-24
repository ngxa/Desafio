# Desafio
Esses dados vão para a AWS, onde uma função (Lambda) faz os cálculos ou análises. O resultado é guardado na nuvem (S3) e mostrado de volta na tela do usuário. Assim, ele vê o resultado na hora e pode consultar depois o que ficou salvo.

A pessoa entra no site e preenche os dados em um formulário.
Quando ela clica em “Enviar”, o site manda essas informações para a AWS.
Lá dentro da AWS, um sistema automático (chamado Lambda) pega os dados e faz as contas ou análises necessárias.
Depois que termina, ele guarda o resultado em um espaço de armazenamento (chamado S3), para ficar salvo.
Em seguida, o resultado volta para o site, e a pessoa já vê o que foi calculado.
Mais tarde, se quiser, ela pode acessar de novo e ver os resultados que ficaram salvos.
