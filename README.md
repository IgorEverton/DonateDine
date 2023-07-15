# DonateDine
Um modelo para reconhecimento de fruta boas e ruins para o consumo.

## Descrição

O modelo para reconhecimento de fruta está sendo treinado com 6 classes. Inicialmente, o modelo foi treinado com 10 classes, mas a acurácia reduziu consideravelmente, o que levou à redução do número de classes para permitir a conclusão do treinamento do modelo. As outras classes estão disponíveis nas pastas de dados. Para adicionar essas classes ao modelo, basta adicionar o nome das pastas ao array 'classes_frutas'. Para executar o código, adicione as pastas no Colab e as classes-alvo devem ter o mesmo nome das pastas que contêm as respectivas frutas. Além disso, atualize o array 'classes_frutas' com as classes de frutas adicionais, mantendo a ordem alfabética padrão do Colab.Ao tentar testar uma imagem, a célula solicitará acesso ao seu explorador de arquivos para selecionar o diretório onde a imagem está localizada. Em seguida, o modelo fará a predição com base nessa imagem.
