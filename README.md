В задании реализована модель - сверточная нейронная сеть  
Модель реализована на pytorch  
accuracy на d_test 95%  


Дополнения:  
  LBL1 - прокси Класс MyDataSet для DataLoader, который перемешивает выборку и делит на батчи  
  LBL2 - Валидация модели на части обучающей выборки  
  LBL3 - Вывод функции потерь на трейне и валидационной части  
  LBL4 - График функции потерь трейна и валдиации от номера эпохи  

  использовался класс torch.optim.lr_scheduler.MultiStepLR для уменьшения learning rate  
