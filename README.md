# (ART ML)[https://www.хакатоны.рус/tpost/uo8cdll0h1-russian-art-ml-challenge-2024?ysclid=m2apgu10k2709960465]
- Был дан датасет с изображениями различных типов народного художества.
- Доля тестовой выборки 15%, тренировочная аугментирована. 
- Дообучалась модель timm/beitv2_large_patch16_224.in1k_ft_in22k_in1k с использованием смешанной точности (https://huggingface.co/timm/beitv2_large_patch16_224.in1k_ft_in22k)
- Размер батча, lr и другие можно увидеть в ноутбке
- Accuracy вышел 85%, можно поднять до 90+ если убрать веса классов на кросс энтропии и сильнее увеличить обучющий набор через аугментацию
