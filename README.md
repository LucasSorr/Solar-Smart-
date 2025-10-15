☀️ SolarSmart — Sistema de Cálculo e Monitoramento de Energia Solar Residencial

Projeto Interdisciplinar - Sistemas de Informação (3ºA / 2025)
Alinhado ao ODS 7 – Energia Limpa e Acessível

🧩 Visão Geral

O SolarSmart é um sistema inteligente que auxilia residências na transição para energia solar, tornando o processo mais acessível, transparente e sustentável.

O projeto calcula a demanda energética com base nos eletrodomésticos e cômodos de um imóvel, determina a quantidade ideal de painéis solares, estima o custo total da instalação e o tempo de retorno do investimento.

Além disso, conecta o usuário a fornecedores de tecnologia fotovoltaica, oferecendo orçamentos personalizados e reduzindo custos com intermediações desnecessárias.

🌍 Motivação

O aumento das tarifas de energia e a dependência de fontes não renováveis tornam urgente o uso de alternativas sustentáveis.
A energia solar pode reduzir a conta de luz em até 95%, gerar empregos e promover inclusão social, especialmente em regiões isoladas.

O SolarSmart visa democratizar o acesso à energia limpa no Brasil, utilizando tecnologias de IoT (Arduino) e sistemas web inteligentes.

⚙️ Funcionalidades Principais

✅ Cadastro e autenticação de usuários
✅ Registro de imóveis, cômodos e eletrodomésticos
✅ Cálculo automático do consumo energético por cômodo e total
✅ Estimativa de custo e retorno do investimento
✅ Conexão com fornecedores de painéis solares
✅ Geração de relatório completo de orçamento

🧠 Arquitetura e Modelagem

O sistema segue o paradigma de Programação Orientada a Objetos (POO) e utiliza um banco de dados relacional modelado para garantir integridade e escalabilidade.

🔸 Principais Classes

Usuário → cadastro, login e associação com imóveis

Imóvel → gerencia cômodos e endereços

Cômodo → agrupa e calcula consumo dos eletrodomésticos

Eletrodoméstico → define potência e tempo de uso

PainelSolar → calcula produção e quantidade ideal de placas

Orçamento → gera estimativas financeiras

Fornecedor / Marca → armazena dados de fornecedores e painéis

🧩 Modelagem de Negócios

Usuário se cadastra e informa dados do imóvel e cômodos

O sistema realiza cálculo de consumo energético

Gera orçamento personalizado e quantidade de painéis recomendada

Conecta com fornecedores cadastrados

Entrega relatório final com custos e plano de instalação

🗄️ Banco de Dados

Estruturado em múltiplas entidades relacionadas, como:

USUARIOS, IMOVEIS, COMODOS, ELETRODOMESTICOS, ORCAMENTO,
PAINEL_SOLARES, MARCAS, FORNECEDORES, REGIOES, CIDADES, ESTADOS, BAIRROS.

As chaves primárias e estrangeiras garantem integridade referencial e normalização dos dados.

💡 Tecnologias Utilizadas

Linguagem: Java (POO)

Banco de Dados: Oracle / SQL

Hardware: Arduino (para monitoramento de consumo)

Conceitos Aplicados: Herança, Agregação, Composição, CRUD, Hash de senhas

ODS Alinhado: #7 – Energia Limpa e Acessível

🧪 Resultados Esperados

🔹 Cálculo de energia solar preciso e automatizado
🔹 Redução de custos para famílias e pequenas empresas
🔹 Facilitação da adoção de energia limpa
🔹 Educação energética e sustentabilidade

👨‍💻 Equipe
Nome	RA
Charles Pereira dos Santos	116442
Diego Pires Aragão	116338
Renato Pires Filogenio	116465
Lucas Pianca Soares	116835
Helder Amaral Junior	117229
Nicolas Righi	116591
📚 Referências

Portal Solar — Como calcular energia solar

Eletrogate — Medidor de corrente e energia com Arduino

INMETRO — Eficiência Energética

ANEEL — Consumo Consciente

Procel — Guia de Eficiência Energética

🧾 Licença

Este projeto é de uso educacional e open-source, podendo ser reutilizado e adaptado com os devidos créditos à equipe desenvolvedora.
