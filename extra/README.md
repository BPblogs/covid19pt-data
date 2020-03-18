# 🧱 Estrutura

O repositório está organizado da seguinte forma:
+ `noticias/`: Dados da categoria "Notícias"
+ `populacional/`: Dados da categoria "Populacional"
+ `medidas_governamentais/`: Dados das medidas governamentais ordenadas por data

## 📰 Notícias

De momento, contém apenas um 

+ `download_listanoticias_publico.ipynb`: notebook Python para fazer download da data, título e descrição de notícias do Público relacionadas 
com o coronavírus. (Um obrigado ao Rui Barros pela ajuda!)
+ `news_sample.csv`: Exemplo de um output do notebook acima.

## 🧑 Populacional

Contém dois datasets descritivos da população portuguesa, do PORDATA:

- [Densidade Populacional](https://www.pordata.pt/Municipios/Densidade+populacional-452)
- [Índice de dependência de idosos](https://www.pordata.pt/Municipios/%C3%8Dndice+de+depend%C3%AAncia+de+idosos-461)

É fornecido o ficheiro acima, para 2018, e uma versão simplificada em CSV, contendo as contagens para as regiões NUTS II (Usadas pela DGS para reportar os casos)


## :bank: Medidas Governamentais

Contém csv contendo as medidas governamentais tomadas em cada data desde o início do surto. Baseado em:

- [Website da República Portuguesa](https://www.portugal.gov.pt/)
- [Pandemia de COVID-19 em Portugal](https://pt.m.wikipedia.org/wiki/Pandemia_de_COVID-19_em_Portugal)

