# Recursos Livres Disponíveis no :fox_face: [GitLab](https://gitlab.com/falabrasil) :fox_face: do FalaBrasil

:fox_face:
Movemos para o GitLab: https://gitlab.com/falabrasil
:fox_face:

:uk:
English version available in [README.en.md](./README.en.md)
:uk:

🇦🇺🇦🇱🇧🇪🇫🇷🇩🇰🇵🇱🇺🇦🇬🇧🇺🇸

## Sumário
- [Árvore de Grupos do Gitlab](#árvore-de-grupos-do-gitLab) :deciduous_tree:
- [Corpora de Áudio Transcrito](#corpora-de-áudio-transcrito) :notes:
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
      <li> <a href="https://gitlab.com/fb-text-corpora"                                      >:open_file_folder:</a> <tt>fb-text-corpora/</tt>         
        <ul>
          <li> <a href="https://gitlab.com/fb-textcorpora/cetenfolha"                        >:fox_face:</a>         <tt>cetenfolha.git</tt>           </li>
          <li> <a href="https://gitlab.com/fb-textcorpora/wordlist"                          >:fox_face:</a>         <tt>wordlist.git</tt>             </li>
        </ul>
      </li>
      <li> <a href="https://gitlab.com/fb-apps"                                              >:open_file_folder:</a> <tt>fb-apps/</tt>                 </li>
      <li> <a href="https://gitlab.com/fb-tts"                                               >:open_file_folder:</a> <tt>fb-tts/</tt>                  </li>
      <li> <a href="https://gitlab.com/fb-asr"                                               >:open_file_folder:</a> <tt>fb-asr/</tt>
        <ul>
          <li> <a href="https://gitlab.com/fb-asr/fb-asr-resources"                          >:open_file_folder:</a> <tt>fb-asr-resources/</tt>  
            <ul>
              <li> <a href="https://gitlab.com/fb-asr/fb-asr-resources/cmusphinx-resources"  >:fox_face:</a>         <tt>cmusphinx-resources.git</tt>  </li>
              <li> <a href="https://gitlab.com/fb-asr/fb-asr-resources/kaldi-resources"      >:fox_face:</a>         <tt>kaldi-resources.git</tt>      </li>
              <li> <a href="https://gitlab.com/fb-asr/fb-asr-resources/htk-resources"        >:fox_face:</a>         <tt>htk-resources.git</tt>        </li>
              <li> <a href="https://gitlab.com/fb-asr/fb-asr-resources/deepspeech-resources" >:fox_face:</a>         <tt>deepspeech-resources.git</tt> </li>
            </ul>
          </li>
          <li> <a href="https://gitlab.com/fb-asr/fb-lm-tutorial"                            >:open_file_folder:</a> <tt>fb-lm-tutorial/</tt>    
            <ul>
              <li> <a href="https://gitlab.com/fb-asr/fb-lm-tutorial/htk-lm-train"           >:fox_face:</a>         <tt>htk-lm-train.git</tt>         </li>
              <li> <a href="https://gitlab.com/fb-asr/fb-lm-tutorial/strilm-lm-train"        >:fox_face:</a>         <tt>srilm-lm-train.git</tt>       </li>
            </ul>
          </li>
          <li> <a href="https://gitlab.com/fb-asr/fb-am-tutorial"                            >:open_file_folder:</a> <tt>fb-am-tutorial/</tt>    
            <ul>
              <li> <a href="https://gitlab.com/fb-asr/fb-am-tutorial/cmusphinx-am-train"     >:fox_face:</a>         <tt>cmusphinx-am-train.git</tt>   </li>
              <li> <a href="https://gitlab.com/fb-asr/fb-am-tutorial/kaldi-am-train"         >:fox_face:</a>         <tt>kaldi-am-train.git</tt>       </li>
              <li> <a href="https://gitlab.com/fb-asr/fb-am-tutorial/htk-am-train"           >:fox_face:</a>         <tt>htk-am-train.git</tt>         </li>
              <li> <a href="https://gitlab.com/fb-asr/fb-am-tutorial/deepspeech-am-train"    >:fox_face:</a>         <tt>deepspeech-am-train.git</tt>  </li>
            </ul>
          </li>
        </ul>
      </li>
      <li> <a href="https://gitlab.com/fb-nlp"                                               >:open_file_folder:</a> <tt>fb-nlp/</tt>            
        <ul>
          <li> <a href="https://gitlab.com/fb-nlp/nlp-generator"                             >:fox_face:</a> <tt>nlp-generator.git</tt>                </li>
          <li> <a href="https://gitlab.com/fb-nlp/nlp-resources"                             >:fox_face:</a> <tt>nlp-resources.git</tt>                </li>
        </ul>
      </li>
      <li> <a href="https://gitlab.com/fb-audio-corpora"                                     >:open_file_folder:</a> <tt>fb-audio-corpora/</tt>  
        <ul>
          <li> <a href="https://gitlab.com/fb-audio-corpora/constituicao16k"                 >:fox_face:</a> <tt>constituicao16k.git</tt>              </li>
          <li> <a href="https://gitlab.com/fb-audio-corpora/codigodefesaconsumidor16k"       >:fox_face:</a> <tt>codigodefesaconsumidor16k.git</tt>    </li>
          <li> <a href="https://gitlab.com/fb-audio-corpora/lapsbm16k"                       >:fox_face:</a> <tt>lapsbm16k.git</tt>                    </li>
          <li> <a href="https://gitlab.com/fb-audio-corpora/lapsmail16k"                     >:fox_face:</a> <tt>lapsmail16k.git</tt>                  </li>
        </ul>
      </li>
    </ul>
  </td>
  <td>
    <ul>
      <li> <a href="https://gitlab.com/fb-text-corpora"  >:deciduous_tree:</a>  Corpora de Texto                              
        <ul>
          <li> <a href="https://gitlab.com/fb-textcorpora/cetenfolha"                        >:fox_face:</a> CETENFolha                                </li>
          <li> <a href="https://gitlab.com/fb-textcorpora/wordlist"                          >:fox_face:</a> Lista de Palavras                         </li>
        </ul>
      </li>
      <li> <a href="https://gitlab.com/fb-apps"                                              >:deciduous_tree:</a> Aplicações em Fala                  </li>
      <li> <a href="https://gitlab.com/fb-tts"                                               >:deciduous_tree:</a> Síntese de Fala                     </li>
      <li> <a href="https://gitlab.com/fb-asr"                                               >:deciduous_tree:</a> Reconhecimento Automático de Fala   
        <ul>
          <li> <a href="https://gitlab.com/fb-asr/fb-asr-resources"                          >:leaves:</a> Recursos prontos para ASR                     
            <ul>
              <li> <a href="https://gitlab.com/fb-asr/fb-asr-resources/cmusphinx-resources"  >:fox_face:</a> CMU Sphinx                                </li>
              <li> <a href="https://gitlab.com/fb-asr/fb-asr-resources/kaldi-resources"      >:fox_face:</a> Kaldi                                     </li>
              <li> <a href="https://gitlab.com/fb-asr/fb-asr-resources/htk-resources"        >:fox_face:</a> HTK                                       </li>
              <li> <a href="https://gitlab.com/fb-asr/fb-asr-resources/deepspeech-resources" >:fox_face:</a> DeepSpeech                                </li>
            </ul>
          </li>
          <li> <a href="https://gitlab.com/fb-asr/fb-lm-tutorial"                            >:leaves:</a> Tutoriais para treino de modelos de linguagem 
            <ul>
              <li> <a href="https://gitlab.com/fb-asr/fb-lm-tutorial/htk-lm-train"           >:fox_face:</a> HTK                                       </li>
              <li> <a href="https://gitlab.com/fb-asr/fb-lm-tutorial/strilm-lm-train"        >:fox_face:</a> SRILM                                     </li>
            </ul>
          </li>
          <li> <a href="https://gitlab.com/fb-asr/fb-am-tutorial"                            >:leaves:</a> Tutoriais para treino de modelos acústicos    
            <ul>
              <li> <a href="https://gitlab.com/fb-asr/fb-am-tutorial/cmusphinx-am-train"     >:fox_face:</a> CMU Sphinx                                </li>
              <li> <a href="https://gitlab.com/fb-asr/fb-am-tutorial/kaldi-am-train"         >:fox_face:</a> Kaldi                                     </li>
              <li> <a href="https://gitlab.com/fb-asr/fb-am-tutorial/htk-am-train"           >:fox_face:</a> HTK                                       </li>
              <li> <a href="https://gitlab.com/fb-asr/fb-am-tutorial/deepspeech-am-train"    >:fox_face:</a> DeepSpeech                                </li>
            </ul>
          </li>
        </ul>
      </li>
      <li> <a href="https://gitlab.com/fb-nlp"                                               >:deciduous_tree:</a> Processamento de Linguagem Natural              
        <ul>
          <li> <a href="https://gitlab.com/fb-nlp/nlp-generator"                             >:fox_face:</a> Gerador de Ferramentas NLP                </li>
          <li> <a href="https://gitlab.com/fb-nlp/nlp-resources"                             >:fox_face:</a> Recursos Prontos para NLP                 </li>
        </ul>
      </li>
      <li> <a href="https://gitlab.com/fb-audio-corpora"                                     >:deciduous_tree:</a> Corpora de Áudio Transcrito                     
        <ul>
          <li> <a href="https://gitlab.com/fb-audio-corpora/constituicao16k"                 >:fox_face:</a> Constituição Federal                      </li>
          <li> <a href="https://gitlab.com/fb-audio-corpora/codigodefesaconsumidor16k"       >:fox_face:</a> Código de Defesa do Consumidor            </li>
          <li> <a href="https://gitlab.com/fb-audio-corpora/lapsbm16k"                       >:fox_face:</a> LaPS Benchmark                            </li>
          <li> <a href="https://gitlab.com/fb-audio-corpora/lapsmail16k"                     >:fox_face:</a> LaPS Mail                                 </li>
        </ul>
      </li>
    </ul>
  </td>
</tbody>
</table>
<!--end=html-->  

## Corpora de Áudio Transcrito
:link: https://gitlab.com/fb-audio-corpora
- Constituição Federal:           https://gitlab.com/fb-audio-corpora/constituicao16k
- Código de Defesa do Consumidor: https://gitlab.com/fb-audio-corpora/codigodefesaconsumidor16k
- Laps Mail:                      https://gitlab.com/fb-audio-corpora/lapsmail16k
- Laps Benchmark:                 https://gitlab.com/fb-audio-corpora/lapsbm16k

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

[Subir :top:](#sumário)

__Grupo FalaBrasil (2019)__    
__Universidade Federal do Pará (UFPA)__    
https://ufpafalabrasil.gitlab.io/     
Created by [@cassiobatista](https://github.com/cassiobatista)
