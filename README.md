# Espectrograma e Detecção de Onsets

Este é um programa desenvolvido em python utilizando Jupyter Notebook para plotar o espectrograma e detectar onsets em arquivos de áudio WAV.

Os arquivos de áudio que utilizei possuem 16 bits de profundidade de amostra e 44100 Hz de taxa de amostragem, mas o programa funciona sem problemas com arquivos de outras configurações (exceto arquivos de 24 bits de profundidade de amostra).

O programa funciona tanto com arquivos mono quanto stereo, somente com a diferença de que para arquivos stereo será plotado um espectrograma para cada canal (L e R), e o mesmo ocorre para a plotagem das funções de detecção de onsets.
