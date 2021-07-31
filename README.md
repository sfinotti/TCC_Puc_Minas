# TCC Puc-Minas
## Ensaios sobre viabilidade de uso de ML para previsão em eleições para vereador

### Links principais:

- [Video: Apresentação resumida do projeto](https://youtu.be/wU1AMn5kFoQ)
- [Texto: TCC - Ensaios sobre viabilidade de uso de ML em eleições para vereador](https://github.com/sfinotti/TCC_Puc_Minas/blob/main/TCC_big_data_silvio_finotti_final.pdf)
- [Canvas: Workflow do TCC](https://github.com/sfinotti/TCC_Puc_Minas/blob/main/TCC_Workflow_Canvas.pdf)
- 


### Descrição dos arquivos:

- [tcc_eleicoes_001_base_2008.ipynb](https://github.com/sfinotti/TCC_Puc_Minas/blob/main/tcc_eleicoes_001_base_2008.ipynb): 
Notebook principal, onde executamos a leitura das diversas fontes de dados, tratamento, junçao e criação do dataset principal. 
Aqui também está o primeiro modelo de Machine Learningdos Decision Tree.

- [tcc_eleicoes_pycaret_v5.ipynb](https://github.com/sfinotti/TCC_Puc_Minas/blob/main/tcc_eleicoes_pycaret_v5.ipynb): 
Notebook com teste de diversos modelos de ML, usando a ferramenta Pycaret.
Executamos ajustes e testes com 5 modelos escolhidos, bem como criamos um novo modelo Ensamble por votação.
Executamos testes de simulação de uma situação de produção, com daddos do ano de 2012, desconhecidos dos modelos

- [tcc_eleicoes_002_leitura_tratamento_base_testes_2012.ipynb](https://github.com/sfinotti/TCC_Puc_Minas/blob/main/tcc_eleicoes_002_leitura_tratamento_base_testes_2012.ipynb): 
Notebook para leitura e tratamento dos dados de candidaturas do ano de 2012, que são usados como "teste de produção" no notebook tcc_eleicoes_pycaret_v5.ipynb

- [\tse](https://github.com/sfinotti/TCC_Puc_Minas/tree/main/tse): 
Pasta com arquivos baixados do repositório do TSE e que são usados nos notebooks deste trabalho

- [\ibge](https://github.com/sfinotti/TCC_Puc_Minas/tree/main/ibge): 
Pasta com arquivos baixados do site do IBGE com informações de municípios, distritos e subdistritos usados nos notebooks deste trabalho


