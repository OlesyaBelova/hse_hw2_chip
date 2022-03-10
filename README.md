Ссылка на Google Collab: https://colab.research.google.com/drive/1WjcBcb6ny5ItmRgk_TNbeQC9TR8aglsA?usp=sharing  
Для анализа была выбрана гистоновая метка H3K9me2 в клеточной линии PC-9.  
# Проверка и подрезание чтений  
Анализ FastQC показал, что выбранные чтения довольно средние по качеству, с не самыми удачными Per tile sequence quality, Per base sequence content и Per sequence GC content. Подрезание чтений не сильно повлияло на эти параметры, но позволило несколько улучшить общее качество, поэтому я решила работать дальше с подрезанными чтениями.  
## Образец ENCFF076WXX  
ДО | ПОСЛЕ  
--- | ----  
![](data/WXX1.png) | ![](data/WXXT1.png)   
![](data/WXX2.png) | ![](data/WXXT2.png)   
![](data/WXX3.png) | ![](data/WXXT3.png)   
![](data/WXX4.png) | ![](data/WXXT4.png)   
## Образец ENCFF824IQO  
ДО | ПОСЛЕ  
--- | ----  
