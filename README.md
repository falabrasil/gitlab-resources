# Recursos Disponíveis no GitLab do FalaBrasil

:fox:
Movemos para o GitLab: https://gitlab.com/falabrasil
:fox:

**NOTE**: English version available in [README.en.md](./README.en.md)

## Sumário
**NOTA**: subseções só serão clicáveis se estiverem expandidas mais abaixo (botões "clique para expandir")

- [Árvore de Grupos do Gitlab](#árvore-de-grupos-do-gitLab)   
- [Corpora de Áudio Transcrito](#corpora-de-áudio-transcrito)
    - [Constituição federal](#constituição-federal)
    - [Código de defesa do consumidor](#código-de-defesa-do-consumidor)
    - [Laps mail](#laps-mail)
    - [Laps benchmark](#laps-benchmark)
- [Corpora de Texto](#corpora-de-texto)
- [Reconhecimento Automático de Fala](#reconhecimento-automático-de-fala)
    - [Recursos prontos](#recursos-prontos)
    - [Tutoriais para treino de modelos acústicos](#tutoriais-para-treino-de-modelos-acústicos)
    - [Tutoriais para treino de modelos de linguagem](#tutoriais-para-treino-de-modelos-de-linguagem)
- [Síntese de Fala](#síntese-de-fala)
- [Processamento de Linguagem Natural](#processamento-de-linguagem-natural)

## Árvore de Grupos do GitLab
<!--begin=html--> 
<details>
<summary>Clique para expandir</summary>
<table>
<tbody>
	<td>
		<ul>
			<li> <a href="https://gitlab.com/fb-text-corpora"                  >:open_file_folder:</a> :earth_americas: <tt>fb-text-corpora/</tt>  </li>
			<li> <a href="https://gitlab.com/fb-align"                         >:open_file_folder:</a> :earth_americas: <tt>fb-align/</tt>         </li>
			<li> <a href="https://gitlab.com/fb-apps"                          >:open_file_folder:</a> :earth_americas: <tt>fb-apps/</tt>          </li>
			<li> <a href="https://gitlab.com/fb-tts"                           >:open_file_folder:</a> :earth_americas: <tt>fb-tts/</tt>           </li>
			<li> <a href="https://gitlab.com/fb-asr"                           >:open_file_folder:</a> :earth_americas: <tt>fb-asr/</tt>
				<ul>
					<li> <a href="https://gitlab.com/fb-asr/fb-lm-tutorial"    >:open_file_folder:</a> :earth_africa:   <tt>fb-lm-tutorial/</tt>    </li>
					<li> <a href="https://gitlab.com/fb-asr/fb-asr-resources"  >:open_file_folder:</a> :earth_africa:   <tt>fb-asr-resources/</tt>  </li>
					<li> <a href="https://gitlab.com/fb-asr/fb-am-tutorial"    >:open_file_folder:</a> :earth_africa:   <tt>fb-am-tutorial/</tt>    </li>
				</ul>
			</li>
			<li> <a href="https://gitlab.com/fb-nlp"                           >:open_file_folder:</a> :earth_americas: <tt>fb-nlp/</tt>            </li>
			<li> <a href="https://gitlab.com/fb-audio-corpora"                 >:open_file_folder:</a> :earth_americas: <tt>fb-audio-corpora/</tt>  </li>
		</ul>
	</td>
	<td>
		<ul>
			<li> <a href="https://gitlab.com/fb-text-corpora"  >:deciduous_tree:</a>  :earth_americas: Corpora de Texto                              </li>
			<li> <a href="https://gitlab.com/fb-align"         >:deciduous_tree:</a>  :earth_americas: Alinhamento Fonético                          </li>
			<li> <a href="https://gitlab.com/fb-apps"          >:deciduous_tree:</a>  :earth_americas: Aplicações em Fala                            </li>
			<li> <a href="https://gitlab.com/fb-tts"           >:deciduous_tree:</a>  :earth_americas: Síntese de Fala                               </li>
			<li> <a href="https://gitlab.com/fb-asr"           >:deciduous_tree:</a>  :earth_americas: Reconhecimento Automático de Fala
				<ul>
					<li> :leaves:                                                     :earth_africa:   Tutoriais para treino de modelos de linguagem </li>
					<li> :leaves:                                                     :earth_africa:   Recursos prontos para ASR                     </li>
					<li> :leaves:                                                     :earth_africa:   Tutoriais para treino de modelos acústicos    </li>
				</ul>
			</li>
			<li> <a href="https://gitlab.com/fb-nlp"          >:deciduous_tree:</a> :earth_americas: Processamento de Linguagem Natural            </li>
			<li> <a href="https://gitlab.com/fb-audio-corpora">:deciduous_tree:</a> :earth_americas: Corpora de Áudio Transcrito                   </li>
		</ul>
	</td>
</tbody>
</table>
</details>
<!--end=html-->  

## Corpora de Áudio Transcrito
Localização: https://gitlab.com/fb-audio-corpora

<details>
<summary>Clique para expandir</summary>

### Constituição federal
Localização: https://gitlab.com/fb-audio-corpora/constituicao16k

> Corpus de voz da Constituição Federal. Os arquivos de áudio foram reamostrados
para 16.000 Hz com 16 bits. Em seguida, os arquivos foram segmentados em
arquivos menores, com aproximadamente 30 segundos de duração cada, e por fim
transcritos. Atualmente, o corpus é composto por um único locutor do sexo
masculino.  Os arquivos totalizam aproximadamente 9 horas de áudio. O ambiente
de gravação utilizado é bastante controlado.

### Código de defesa do consumidor
Localização: https://gitlab.com/fb-audio-corpora/codigodefesaconsumidor16k

### Laps mail
Localização: https://gitlab.com/fb-audio-corpora/lapsmail16k

> Corpus de voz que representa o contexto de uma aplicação de correio 
eletrônico, utilizado para a avaliação de sistemas LVCSR para tarefas de comando
e controle. Atualmente, composto por 86 sentenças (43 comando e 43 nomes
próprios) gravados por 25 voluntários (21 homens e 4 mulheres), o que
corresponde a 84 minutos minutos de áudio com um vocabulário de 95 palavras. As
gravações foram realizadas com um microfone de alta qualidade (Shure PG30) em um
ambiente de gravação não controlado.

### Laps benchmark
Localização: https://gitlab.com/fb-audio-corpora/lapsbm16k

> Corpus de voz utilizado para avaliação de desempenho de sistemas LVCSR.
Atualmente composto por 700 frases, o corpus possui 35 locutores com 20 frases
cada, sendo 25 homens e 10 mulheres, o que corresponde a aproximadamente 54
minutos de áudio. Este corpus será expandido de forma a ter 50 locutores com a
mesma distribuição, totalizando 1.000 frases. Todas as gravações foram
realizadas em computadores utilizando microfones comuns. A taxa de amostragem
utilizada foi de 16.000 Hz e cada amostra foi representada com 16 bits. O
ambiente não foi controlado, existindo a presença de ruído nas gravações, com
isso busca-se caracterizar ambientes onde software de reconhecimento de voz são
utilizados.
</details>

## Corpora de Texto
Localização: https://gitlab.com/fb-text-corpora

## Reconhecimento Automático de Fala
Localização: https://gitlab.com/fb-asr

### Recursos prontos
Localização: https://gitlab.com/fb-asr/fb-asr-resources
- CMU Sphinx: https://gitlab.com/fb-asr/fb-asr-resources/cmusphinx-resources
- Kaldi:      https://gitlab.com/fb-asr/fb-asr-resources/kaldi-resources
- HTK:        https://gitlab.com/fb-asr/fb-asr-resources/htk-resources
- DeepSpeech: https://gitlab.com/fb-asr/fb-asr-resources/deepspeech-resources

### Tutoriais para treino de modelos acústicos
Localização: https://gitlab.com/fb-asr/fb-am-tutorial
- CMU Sphinx: https://gitlab.com/fb-asr/fb-am-tutorial/cmusphinx-am-train
- Kaldi:      https://gitlab.com/fb-asr/fb-am-tutorial/kaldi-am-train
- HTK:        https://gitlab.com/fb-asr/fb-am-tutorial/htk-am-train
- DeepSpeech: https://gitlab.com/fb-asr/fb-am-tutorial/deepspeech-am-train

### Tutoriais para treino de modelos de linguagem
Localização: https://gitlab.com/fb-asr/fb-lm-tutorial
- HTK:   https://gitlab.com/fb-asr/fb-lm-tutorial/htk-lm-train
- SRILM: https://gitlab.com/fb-asr/fb-lm-tutorial/srilm-lm-train

## Síntese de Fala
Localização: https://gitlab.com/fb-tts

## Processamento de Linguagem Natural
Localização: https://gitlab.com/fb-nlp
- Software gerador de recursos: https://gitlab.com/fb-nlp/nlp-generator
    - G2P: conversor grafema-fonema
    - Syll: separador silábico
    - Stress: identificador de vogal tônica
    - HH: desambiguador de homófonos-heterófonos :warning:
- Recursos prontos :warning: : https://gitlab.com/fb-nlp/nlp-resources
    - Lista de Palavras?
    - Dicionários Fonéticos (seed lexicon)
    - Dicionário de separação silábica

[Subir :top:](#recursos-disponíveis-no-gitlab-do-falabrasil)

__Grupo FalaBrasil (2019)__    
__Universidade Federal do Pará (UFPA)__    
Cassio Batista - cassio.batista.13@gmail.com
