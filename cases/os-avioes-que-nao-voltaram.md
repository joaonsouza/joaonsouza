# Os aviões que não voltaram: o que o viés do sobrevivente ensina sobre monitorar dados

## Problema
Em 1943, a força aérea americana queria saber onde blindar os bombardeiros: mapearam os buracos de bala nos aviões que voltavam da missão e planejavam reforçar os pontos mais atingidos. Um estatístico apontou o erro que mudou a estratégia — os aviões que realmente importavam eram os que não voltaram para serem contados.

Esse mesmo erro se repete todos os dias em monitoramento de dados. A prática mais comum é alertar quando uma pipeline falha, mas o dado mais perigoso não é o que quebra: é o que nunca chega a gerar um erro. Uma pipeline pode terminar, marcar verde, e trazer uma linha onde deveria trazer milhões; uma fonte pode parar de enviar registros há dias sem disparar nenhum alerta.

## Abordagem
A partir de casos reais de operação de plataformas analíticas, um framework prático para ir além do "a pipeline completou?": as seis dimensões de qualidade de dados do DAMA-DMBOK — completude, validade, acurácia, consistência, timeliness e unicidade — traduzidas em checks concretos, aplicáveis em qualquer stack de dados moderna.

## Dados & Ferramentas
Monitoramento de pipelines e plataformas analíticas, checks de qualidade de dados baseados nas dimensões DAMA-DMBOK.

## Resultado
Checklist de monitoramento de dados que cobre também os "aviões que não voltaram" — os problemas que hoje não disparam nenhum alerta na plataforma.

---
_Palestra submetida ao MVPConf 2026._
