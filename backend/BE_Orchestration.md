### Backend Orchestration

Para este sistema o único workflow para o qual seria necessária backend orchestration seria para o de dar feedback a um produto.

O workflow, que necessita de orchestration no backend é o seguinte:

1. Verificar que o produto existe
2. Verificar que o utilizador existe (e outras verificações de segurança)
3. Inserir o novo feedback

Esta orchestration tem de ser no backend, porque é um "business critical" workflow. Isto porque o frontend é "dumb" neste aspeto. Portanto é necessário um workflow que garanta um bom comportamento desta operação, de forma a garantir que não são feitos "ataques", a produtos ou mercados com algum mecanismo que tenha alto impacto no seu rating.
