# Covid-x-ray


dataset 1: raw inage shape : (299,299,3)  

 https://www.kaggle.com/tawsifurrahman/covid19-radiography-database
 
=> (299,299,3)->greyscale->resahpe->(224,224) and then fitting to Alexnet
=> (299,299,3)->greyscale-> add block before Alexnet (block output -> (224,224))


dataset 2: raw image shape : (1024,1024,3)

https://data.mendeley.com/datasets/9xkhgts2s6/3
