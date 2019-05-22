# Recursos Livres Disponíveis no GitLab do FalaBrasil

:fox_face:
Movemos para o GitLab: https://gitlab.com/falabrasil
:fox_face:

**NOTE**: English version available in [README.en.md](./README.en.md)

## Sumário
**NOTA**: subseções só serão clicáveis se estiverem expandidas mais abaixo (botões "clique para expandir")

- [Árvore de Grupos do Gitlab](#árvore-de-grupos-do-gitLab) :deciduous_tree:
- [Corpora de Áudio Transcrito](#corpora-de-áudio-transcrito) :notes:
    - [Constituição federal](#constituição-federal)
    - [Código de defesa do consumidor](#código-de-defesa-do-consumidor)
    - [Laps mail](#laps-mail)
    - [Laps benchmark](#laps-benchmark)
- [Corpora de Texto](#corpora-de-texto) :book:
- [Reconhecimento Automático de Fala](#reconhecimento-automático-de-fala) :speaking_head: > :computer: > :scroll:
    - [Recursos prontos](#recursos-prontos)
    - [Tutoriais para treino de modelos acústicos](#tutoriais-para-treino-de-modelos-acústicos)
    - [Tutoriais para treino de modelos de linguagem](#tutoriais-para-treino-de-modelos-de-linguagem)
- [Síntese de Fala](#síntese-de-fala) :scroll: > :computer: > :sound:
- [Processamento de Linguagem Natural](#processamento-de-linguagem-natural) :capital_abcd:

## Árvore de Grupos do GitLab
<!--begin=html--> 
<table>
<tbody>
	<td>
		<ul>
			<li> <a href="https://gitlab.com/fb-text-corpora"                  >:open_file_folder:</a> <tt>fb-text-corpora/</tt>  </li>
			<li> <a href="https://gitlab.com/fb-align"                         >:open_file_folder:</a> <tt>fb-align/</tt>         </li>
			<li> <a href="https://gitlab.com/fb-apps"                          >:open_file_folder:</a> <tt>fb-apps/</tt>          </li>
			<li> <a href="https://gitlab.com/fb-tts"                           >:open_file_folder:</a> <tt>fb-tts/</tt>           </li>
			<li> <a href="https://gitlab.com/fb-asr"                           >:open_file_folder:</a> <tt>fb-asr/</tt>
				<ul>
					<li> <a href="https://gitlab.com/fb-asr/fb-asr-resources"  >:open_file_folder:</a> <tt>fb-asr-resources/</tt>  
						<ul>
							<li> <a href="https://gitlab.com/fb-asr/fb-asr-resources/cmusphinx-resources"     >:fox_face:</a> <tt>cmusphinx-resources.git</tt>  </li>
							<li> <a href="https://gitlab.com/fb-asr/fb-asr-resources/kaldi-resources"         >:fox_face:</a> <tt>kaldi-resources.git</tt>      </li>
							<li> <a href="https://gitlab.com/fb-asr/fb-asr-resources/htk-resources"           >:fox_face:</a> <tt>htk-resources.git</tt>        </li>
							<li> <a href="https://gitlab.com/fb-asr/fb-asr-resources/deepspeech-resources"    >:fox_face:</a> <tt>deepspeech-resources.git</tt> </li>
						</ul>
					</li>
					<li> <a href="https://gitlab.com/fb-asr/fb-lm-tutorial"    >:open_file_folder:</a> <tt>fb-lm-tutorial/</tt>    
						<ul>
							<li> <a href="https://gitlab.com/fb-asr/fb-lm-tutorial/htk-am-train"     >:fox_face:</a> <tt>htk-lm-train.git</tt>   </li>
							<li> <a href="https://gitlab.com/fb-asr/fb-lm-tutorial/strilm-am-train"  >:fox_face:</a> <tt>srilm-am-train.git</tt> </li>
						</ul>
					</li>
					<li> <a href="https://gitlab.com/fb-asr/fb-am-tutorial"    >:open_file_folder:</a> <tt>fb-am-tutorial/</tt>    
						<ul>
							<li> <a href="https://gitlab.com/fb-asr/fb-am-tutorial/cmusphinx-am-train"     >:fox_face:</a> <tt>cmusphinx-am-train.git</tt>  </li>
							<li> <a href="https://gitlab.com/fb-asr/fb-am-tutorial/kaldi-am-train"         >:fox_face:</a> <tt>kaldi-am-train.git</tt>      </li>
							<li> <a href="https://gitlab.com/fb-asr/fb-am-tutorial/htk-am-train"           >:fox_face:</a> <tt>htk-am-train.git</tt>        </li>
							<li> <a href="https://gitlab.com/fb-asr/fb-am-tutorial/deepspeech-am-train"    >:fox_face:</a> <tt>deepspeech-am-train.git</tt> </li>
						</ul>
					</li>
				</ul>
			</li>
			<li> <a href="https://gitlab.com/fb-nlp"                           >:open_file_folder:</a> <tt>fb-nlp/</tt>            
				<ul>
					<li> <a href="https://gitlab.com/fb-nlp/nlp-generator"           >:fox_face:</a> <tt>nlp.generator.git</tt>                          </li>
					<li> <a href="https://gitlab.com/fb-nlp/nlp-resources"           >:fox_face:</a> <tt>nlp.resources.git</tt>                          </li>
				</ul>
			</li>
			<li> <a href="https://gitlab.com/fb-audio-corpora"                 >:open_file_folder:</a> <tt>fb-audio-corpora/</tt>  
				<ul>
					<li> <a href="https://gitlab.com/fb-audio-corpora/constituicao16k"           >:fox_face:</a> <tt>constituicao16k.git</tt>            </li>
					<li> <a href="https://gitlab.com/fb-audio-corpora/codigodefesaconsumidor16k" >:fox_face:</a> <tt>codigodefesaconsumidor16k.git</tt>  </li>
					<li> <a href="https://gitlab.com/fb-audio-corpora/lapsbm16k"                 >:fox_face:</a> <tt>lapsbm16k.git</tt>                  </li>
					<li> <a href="https://gitlab.com/fb-audio-corpora/lapsmail16k"               >:fox_face:</a> <tt>lapsmail16k.git</tt>                </li>
				</ul>
			</li>
		</ul>
	</td>
	<td>
		<ul>
			<li> <a href="https://gitlab.com/fb-text-corpora"  >:deciduous_tree:</a>  Corpora de Texto                              </li>
			<li> <a href="https://gitlab.com/fb-align"         >:deciduous_tree:</a>  Alinhamento Fonético                          </li>
			<li> <a href="https://gitlab.com/fb-apps"          >:deciduous_tree:</a>  Aplicações em Fala                            </li>
			<li> <a href="https://gitlab.com/fb-tts"           >:deciduous_tree:</a>  Síntese de Fala                               </li>
			<li> <a href="https://gitlab.com/fb-asr"           >:deciduous_tree:</a>  Reconhecimento Automático de Fala
				<ul>
					<li> :leaves:                                                     Recursos prontos para ASR                     
						<ul>
							<li> <a href="https://gitlab.com/fb-asr/fb-asr-resources/cmusphinx-resources"     >:fox_face:</a> <tt>cmusphinx-resources.git</tt>  </li>
							<li> <a href="https://gitlab.com/fb-asr/fb-asr-resources/kaldi-resources"         >:fox_face:</a> <tt>kaldi-resources.git</tt>      </li>
							<li> <a href="https://gitlab.com/fb-asr/fb-asr-resources/htk-resources"           >:fox_face:</a> <tt>htk-resources.git</tt>        </li>
							<li> <a href="https://gitlab.com/fb-asr/fb-asr-resources/deepspeech-resources"    >:fox_face:</a> <tt>deepspeech-resources.git</tt> </li>
						</ul>
					</li>
					<li> :leaves:                                                     Tutoriais para treino de modelos de linguagem 
						<ul>
							<li> <a href="https://gitlab.com/fb-asr/fb-lm-tutorial/htk-am-train"     >:fox_face:</a> <tt>htk-lm-train.git</tt>   </li>
							<li> <a href="https://gitlab.com/fb-asr/fb-lm-tutorial/strilm-am-train"  >:fox_face:</a> <tt>srilm-am-train.git</tt> </li>
						</ul>
					</li>
					<li> :leaves:                                                     Tutoriais para treino de modelos acústicos    
						<ul>
							<li> <a href="https://gitlab.com/fb-asr/fb-am-tutorial/cmusphinx-am-train"     >:fox_face:</a> CMU Sphinx                </li>
							<li> <a href="https://gitlab.com/fb-asr/fb-am-tutorial/kaldi-am-train"         >:fox_face:</a> Kaldi                     </li>
							<li> <a href="https://gitlab.com/fb-asr/fb-am-tutorial/htk-am-train"           >:fox_face:</a> HTK                       </li>
							<li> <a href="https://gitlab.com/fb-asr/fb-am-tutorial/deepspeech-am-train"    >:fox_face:</a> DeepSpeech                </li>
						</ul>
					</li>
				</ul>
			</li>
			<li> <a href="https://gitlab.com/fb-nlp"          >:deciduous_tree:</a> Processamento de Linguagem Natural              
				<ul>
					<li> <a href="https://gitlab.com/fb-nlp/nlp-generator"           >:fox_face:</a> Gerador de Ferramentas NLP                   </li>
					<li> <a href="https://gitlab.com/fb-nlp/nlp-resources"           >:fox_face:</a> Recursos Prontos para NLP                    </li>
				</ul>
			</li>
			<li> <a href="https://gitlab.com/fb-audio-corpora">:deciduous_tree:</a> Corpora de Áudio Transcrito                     
				<ul>
					<li> <a href="https://gitlab.com/fb-audio-corpora/constituicao16k"           >:fox_face:</a> Constituição Federal                 </li>
					<li> <a href="https://gitlab.com/fb-audio-corpora/codigodefesaconsumidor16k" >:fox_face:</a> Código de Defesa do Consumidor       </li>
					<li> <a href="https://gitlab.com/fb-audio-corpora/lapsbm16k"                 >:fox_face:</a> LaPS Benchmark                       </li>
					<li> <a href="https://gitlab.com/fb-audio-corpora/lapsmail16k"               >:fox_face:</a> LaPS Mail                            </li>
				</ul>
			</li>
		</ul>
	</td>
</tbody>
</table>
<!--end=html-->  

## Corpora de Áudio Transcrito
:link: https://gitlab.com/fb-audio-corpora

<details>
<summary>Clique para expandir</summary>

### Constituição federal
:link: https://gitlab.com/fb-audio-corpora/constituicao16k

> Corpus de voz da Constituição Federal. Os arquivos de áudio foram reamostrados
para 16.000 Hz com 16 bits. Em seguida, os arquivos foram segmentados em
arquivos menores, com aproximadamente 30 segundos de duração cada, e por fim
transcritos. Atualmente, o corpus é composto por um único locutor do sexo
masculino.  Os arquivos totalizam aproximadamente 9 horas de áudio. O ambiente
de gravação utilizado é bastante controlado.

### Código de defesa do consumidor
:link: https://gitlab.com/fb-audio-corpora/codigodefesaconsumidor16k

### Laps mail
:link: https://gitlab.com/fb-audio-corpora/lapsmail16k

> Corpus de voz que representa o contexto de uma aplicação de correio 
eletrônico, utilizado para a avaliação de sistemas LVCSR para tarefas de comando
e controle. Atualmente, composto por 86 sentenças (43 comando e 43 nomes
próprios) gravados por 25 voluntários (21 homens e 4 mulheres), o que
corresponde a 84 minutos minutos de áudio com um vocabulário de 95 palavras. As
gravações foram realizadas com um microfone de alta qualidade (Shure PG30) em um
ambiente de gravação não controlado.

### Laps benchmark
:link: https://gitlab.com/fb-audio-corpora/lapsbm16k

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
:link: https://gitlab.com/fb-text-corpora

## Reconhecimento Automático de Fala
:link: https://gitlab.com/fb-asr

### Recursos prontos
:link: https://gitlab.com/fb-asr/fb-asr-resources
- CMU Sphinx: https://gitlab.com/fb-asr/fb-asr-resources/cmusphinx-resources
- Kaldi:      https://gitlab.com/fb-asr/fb-asr-resources/kaldi-resources
- HTK:        https://gitlab.com/fb-asr/fb-asr-resources/htk-resources
- DeepSpeech: https://gitlab.com/fb-asr/fb-asr-resources/deepspeech-resources

### Tutoriais para treino de modelos acústicos
:link: https://gitlab.com/fb-asr/fb-am-tutorial
- CMU Sphinx: https://gitlab.com/fb-asr/fb-am-tutorial/cmusphinx-am-train
- Kaldi:      https://gitlab.com/fb-asr/fb-am-tutorial/kaldi-am-train
- HTK:        https://gitlab.com/fb-asr/fb-am-tutorial/htk-am-train
- DeepSpeech: https://gitlab.com/fb-asr/fb-am-tutorial/deepspeech-am-train

### Tutoriais para treino de modelos de linguagem
:link: https://gitlab.com/fb-asr/fb-lm-tutorial
- HTK:   https://gitlab.com/fb-asr/fb-lm-tutorial/htk-lm-train
- SRILM: https://gitlab.com/fb-asr/fb-lm-tutorial/srilm-lm-train

## Síntese de Fala
:link: https://gitlab.com/fb-tts

## Processamento de Linguagem Natural
:link: https://gitlab.com/fb-nlp
- Software gerador de recursos: https://gitlab.com/fb-nlp/nlp-generator
    - G2P: conversor grafema-fonema
    - Syll: separador silábico
    - Stress: identificador de vogal tônica
    - HH: desambiguador de homófonos-heterófonos :warning:
- Recursos prontos :warning: : https://gitlab.com/fb-nlp/nlp-resources
    - Lista de Palavras?
    - Dicionários Fonéticos (seed lexicon)
    - Dicionário de separação silábica

[Subir :top:](#recursos-livres-disponíveis-no-gitlab-do-falabrasil)

__Grupo FalaBrasil (2019)__    
__Universidade Federal do Pará (UFPA)__    
Cassio Batista - cassio.batista.13@gmail.com    
https://ufpafalabrasil.gitlab.io/
