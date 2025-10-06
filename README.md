# Dimensão de data no Power BI - código TMDL



Código para geração de dimensão de data no Power BI utilizando a aba "TMDL view". 



Como utilizar:


1. Abrir o Power BI Desktop;
2. Criar um novo relatório em branco ou abrir um projeto existente;
3. Navegar até a aba "TMDL view";
4. Colar o código do arquivo "Script DimData Brasil.tmdl" (disponível neste repositório do Github);
5. (Opcional) Editar no final do script as datas que deseja que sejam geradas (o padrão está de 2010 a 2030);

<img width="1726" height="139" alt="image" src="https://github.com/user-attachments/assets/308e6797-dc23-4d75-aae4-ca5193140bb3" />


6. Clicar em "aplicar as alterações"
7. Após concluído, clicar em "Atualizar agora" para atualização dos dados da dimensão;
8. Confirmar se a tabela "DimData" foi criada e os dados foram carregados corretamente.

Para editar os feriados (incluir, alterar ou remover) utilizar o próprio TMDL view ou abrir a janela do Power Query, localizar a consulta "Feriados" e clicar no botão "Editor avançado".

