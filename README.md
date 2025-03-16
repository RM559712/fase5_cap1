# FIAP - Faculdade de Informática e Administração Paulista

<p align="center">
<a href= "https://www.fiap.com.br/"><img src="assets/images/logo-fiap.png" alt="FIAP - Faculdade de Informática e Admnistração Paulista" border="0" width=40% height=40%></a>
</p>

<br>

# Cap 1 - FarmTech na era da cloud computing

## 👨‍👩 Grupo

Grupo de número <b>40</b> formado pelos integrantes mencionados abaixo.

## 👨‍🎓 Integrantes: 
- <a href="https://www.linkedin.com/in/cirohenrique/">Ciro Henrique</a> ( <i>RM559040</i> )
- <a href="javascript:void(0)">Enyd Bentivoglio</a> ( <i>RM560234</i> )
- <a href="https://www.linkedin.com/in/marcofranzoi/">Marco Franzoi</a> ( <i>RM559468</i> )
- <a href="https://www.linkedin.com/in/rodrigo-mazuco-16749b37/">Rodrigo Mazuco</a> ( <i>RM559712</i> )

## 👩‍🏫 Professores:

### Tutor(a) 
- <a href="https://www.linkedin.com/in/lucas-gomes-moreira-15a8452a/">Lucas Gomes Moreira</a>

### Coordenador(a)
- <a href="https://www.linkedin.com/in/profandregodoi/">André Godoi</a>

## 📜 Descrição

<b>Referência</b>: https://on.fiap.com.br/mod/assign/view.php?id=466125&c=12301

## Entrega 1

<i>Pendente...</i>

## Entrega 2

### Sobre a escolha da AWS

Optamos em utilizar os serviços fornecidos pela AWS pelos seguintes motivos:

- Os recursos são facilmente escalonáveis de acordo com a necessidade. Automaticamente, os serviços são cobrados de acordo com a utilização ou ajustes nas configurações;
- Possui uma infraestrutura global, distribuídos em diferentes regiões do planeta. Com isso, é possível contratar determinados serviços em regiões com valores mais acessíveis;
- Possui diversos protocolos de segurança, garantindo ao máximo a confiabilidade para armazenamento de dados;
- Possui uma ampla documentação para todos os serviços disponibilizados. Além disso, possui um suporte técnico com disponibilidade 24/7;

### Sobre a escolha da região

Optamos em contratar os serviços localizados na região <strong>Leste dos EUA</strong> (<i>N. da Virgínia</i>) por conta do custo mais acessível. Infelizmente, em comparação com a região <strong>América do Sul</strong> (<i>São Paulo</i>), por mais que as configurações definidas sejam idênticas, os custos a médio/longo prazo se tornariam inviáveis. Comparando as duas cotações, a diferença chega em pouco mais de 70%, uma diferença muita alta na qual podemos utilizar em um futuro não muito distante para investirmos em melhorias na infraestrutura de servidores (<i>banco de dados, espaço para armazenamento, CPUs, etc.</i>).

O arquivo contendo as estimativas podem ser visualizados através do arquivo [Estimativas](https://github.com/RM559712/fase5_cap1/blob/main/document/Entrega2/Estimativa.pdf).

Os cálculos de estimativas utilizando as regiões <strong>Leste dos EUA</strong> (<i>N. da Virgínia</i>) e <strong>América do Sul</strong> (<i>São Paulo</i>) foram efetuados a partir do serviço https://calculator.aws e pode ser visualizado através do vídeo <PENDENTE>.

![Image2](https://github.com/RM559712/fase5_cap1/blob/main/assets/images/result.png)

![Image2](https://github.com/RM559712/fase5_cap1/blob/main/assets/images/report.png)

### Sobre o armazenamento de dados

Devido ao fato do sistema não trafegar dados sensíveis, como por exemplo, dados de usuários ou informações específicas, mantivemos a decisão em utilizar os serviços localizados na região <strong>Leste dos EUA</strong> (<i>N. da Virgínia</i>). Teríamos optado em utilizar os serviços localizados na região <strong>América do Sul</strong> (<i>São Paulo</i>) se as funcionalidades desse sistema trafegassem dados sensíveis de usuários, já que a <strong>Lei Geral de Proteção de Dados</strong> (<i>LGPD</i>) aplica regras rigorosas para que esse tipo de informação seja armazenada localmente.

A decisão também levou em consideração o fato do acesso rápido <i>versus</i> a região escolhida. Mesmo concluindo que existem questões envolvendo latência por conta da distância, optamos em adotar boas práticas no desenvolvimento e também análises constantes visando possíveis <i>upgrades</i> na infraestrutura escolhida.

## 📁 Estrutura de pastas

Dentre os arquivos e pastas presentes na raiz do projeto, definem-se:

1. <b>assets</b>: Diretório para armazenamento de arquivos complementares da estrutura do sistema.
    - Diretório "images": Diretório para armazenamento de imagens.

2. <b>config</b>: Diretório para armazenamento de arquivos em formato <i>json</i> contendo configurações.

3. <b>document</b>: Diretório para armazenamento de documentos relacionados ao sistema.

4. <b>scripts</b>: Diretório para armazenamento de scripts.

5. <b>src</b>: Diretório para armazenamento de código fonte do sistema.

6. <b>tests</b>: Diretório para armazenamento de resultados de testes.
	- Diretório "images": Diretório para armazenamento de imagens relacionadas aos testes efetuados.

7. <b>README.md</b>: Documentação do projeto em formato markdown.

<i><strong>Importante</strong>: A estrutura de pastas foi mantida neste formato para atender ao padrão de entrega dos projetos.</i>

## 🔧 Como executar o código

Esse projeto não possui parte técnica para execução.

## 📋 Licença

Desenvolvido pelo Grupo 40 para o projeto da fase 5 (<i>Cap 1 - FarmTech na era da cloud computing</i>) da <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://fiap.com.br">Fiap</a>. Está licenciado sobre <a href="http://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">Attribution 4.0 International</a>.</p>