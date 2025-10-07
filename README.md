# Dimensão de data no Power BI - código TMDL



Código para geração de dimensão de data no Power BI utilizando a aba "TMDL view". 



Como utilizar:


1. Abra o Power BI Desktop: crie um novo relatório em branco ou abra um relatório existente;
2. No menu à esquerda, clique em TMDL View — é a exibição de código do modelo;
3. Abra o arquivo "Script DimData Brasil.tmdl" (disponível neste repositório do Github) e clique no ícone de copiar no canto superior direito;
4. Volte ao Power BI e cole o código na TMDL View;
5. (Opcional) Por padrão, o código cria datas de 2010 a 2030. Se quiser outro intervalo, altere os valores dos parâmetros no final do script:<br><br>

<img width="1726" height="139" alt="image" src="https://github.com/user-attachments/assets/308e6797-dc23-4d75-aae4-ca5193140bb3" />

<br><br>
6. Clique em "Aplicar" no canto superior esquerdo. Isso vai criar a tabela "DimData" automaticamente;<br>
7. Depois, clique em "Atualizar agora" para carregar os dados;<br>
8. Confira o resultado nas abas "model view" ou "report view". Você vai ver a tabela "DimData" completa e pronta para uso;<br>
9. (Opcional) Se quiser alterar os feriados, vá em Transformar dados (ele abrirá a janela do Power Query). <br>
Na consulta Feriados, clique em Editor avançado e edite as linhas — adicionando, removendo ou ajustando as datas e descrições.


