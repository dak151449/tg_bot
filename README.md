# tg_bot

Телеграм бот для переноса стиля с помощью алгоритма "Нейронный перенос стиля с Pytorch" из лекции https://stepik.org/lesson/352804/step/1?unit=472606.
Нейронный перенос стиля -- это алгоритм, который принимает контент-изображение (например, черепаху), стиль-изображение (например, картинку известного художника) и возвращает изображение, которое будто бы нарисовано тем художником.

Бот принимает первую фотографию за стиль, а вторую, к которой нужно приментить этот стиль, и после отправки двух фотографий, отправлет результат через какое-то время.

Вам достаточно написать токен своего бота в 255 строке и запустить код bot.py. Теперь просто пишите своему боту в telegram /start и отправляйте фотографии.
