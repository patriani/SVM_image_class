# SVM_image_class
Diego Queiroz - 5222; Ricardo B. - 5948

#Projeto da disciplina SIN 393 referente à classificação de imagens entre um conjunto de morcegos, maçãs, óssos e bezouro
Para executar o projeto siga as seguintes instruções no prompt de comando:

   $ conda create –n env-proj1-393-py38 python=3.8
   $ conda activate env-proj1-393-py38
   $ pip install sklearn==1.1.3
   $ pip install scikit-image==0.19.3
   $ pip install matplotlib==3.6.0
   $ pip install pandas==1.5.1
   $ pip install seaborn==0.12.1
   $ pip install notebook==6.5.1
  
#Abra o código em seu editor de texto e na linha 32 altere
'/home/diego/Desktop/SVM/mpeg7_4classes_aug_x8_work/' para '/home/"nome do usuário"/"Desktop"/"pasta do trabalho"/"Nome do conjunto"/'

#Altere a pasta de testes para o conjunto "real"

#Nos testes realizados no conjunto que nos foi entregue, obtivemos: 

![Terminal](https://user-images.githubusercontent.com/43487367/207147529-350d83a6-4324-4e91-a5b3-2957b14bdf69.png)

Notas: a normalização foi feita por meio do z-score (de scipy.stats) e validação por meio do K-fold. Essa validação ocorre durante a chamada "model_selection.GridSearchCV{}" em que é passado o parâmetro "CV=10", que define a aplicação do K-fold para 10 conjuntos distintos de validação a partir do conjunto de treino.

Seguem os As matrizes de confusão de Teste:

x-special/nautilus-clipboard
copy
file:///home/diego/Desktop/Teste.png

E Treino:

x-special/nautilus-clipboard
copy
file:///home/diego/Desktop/Treino.png


