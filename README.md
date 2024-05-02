Созданный репозиторий, содержит в себе решение вступительного задания на стажировку VK

Репозиторий состоит из
- VK_spam.ipynb  - файл Jupyter Notebook, с решением задачи
- submission.csv - файл .csv, содержащий 2 колонки
- submission_proba.csv - файл .csv, содержащий 4 колонки 

submission.csv:  
Kолонка text  - содержит исходный текст   
Kолонка score - содержит предсказания модели (объекты с высокими вероятностями ближе к 1 являются спамом, а объекты с низкими вероятностями ближе к 0 - не спамом)    

submission_proba.csv
Kолонка text  - содержит исходный текст   
Kолонка score - содержит предсказания модели (объекты с высокими вероятностями ближе к 1 являются спамом, а объекты с низкими вероятностями ближе к 0 - не спамом)    
Kолонка ham_proba - вероятность принадлежности к классу 'ham'  
Kолонка spam_proba - вероятность принадлежности к классу 'spam'
