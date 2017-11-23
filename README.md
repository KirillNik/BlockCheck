BlockCheck v0.0.9.6
Для получения корректных результатов используйте DNS-сервер провайдера и отключите средства обхода блокировок.

Проверка работоспособности IPv6: IPv6 недоступен.
IP: 178.184.255.xxx, провайдер: Kemerovo Regional Telegraph, branch of Kuzbass Pub/ Ростелеком МРФ "Сибирь"

[O] Тестируем IPv4 DNS
	Через системный DNS:	 ['184.173.136.161', '195.8.215.136', '195.82.146.214', '5.178.68.100', '95.167.13.50', '95.167.13.50']
	Через Google DNS:	 ['104.20.134.45', '104.20.135.45', '104.24.10.70', '104.24.11.70', '184.173.136.161', '195.8.215.136', '195.82.146.214', '5.178.68.100']
	Через Google API:	 ['104.20.134.45', '104.20.135.45', '104.24.10.70', '104.24.11.70', '184.173.136.161', '195.8.215.136', '195.82.146.214', '5.178.68.100']
	Несуществующий DNS не вернул адресов (это не ошибка)
[☠] DNS-записи подменяются
[✓] DNS не перенаправляется

[O] Тестируем HTTP (по настоящим IP-адресам сайтов)
	Открываем  http://a.putinhuylo.com/
[✓] Сайт открывается
	Открываем  http://furry.booru.org/
[✓] Сайт открывается
	Открываем  http://furry.booru.org/index.php?page=post&s=view&id=111173
[✓] Сайт открывается
	Открываем  http://pbooru.com/
[✓] Сайт открывается
	Открываем  http://pbooru.com/index.php?page=post&s=view&id=303026
[✓] Сайт открывается
	Открываем  http://rutracker.org/forum/index.php
[✓] Сайт открывается

[O] Тестируем HTTPS
	Открываем  https://e621.net/
[✓] Сайт открывается
	Открываем  https://lolibooru.moe/
[✓] Сайт открывается
	Открываем  https://rutracker.org/forum/index.php
[✓] Сайт открывается
	Открываем  https://www.dailymotion.com/
[✓] Сайт открывается

[!] Результат:
[⚠] Ваш провайдер подменяет DNS-записи, но не перенаправляет сторонние IPv4 DNS-серверы на свой.
 Вам поможет смена DNS, например, на Яндекс.DNS 77.88.8.8 или Google DNS 8.8.8.8 и 8.8.4.4.
[⚠] Ваш провайдер полностью блокирует доступ к HTTPS-сайтам из реестра.
[⚠] У вашего провайдера "обычный" DPI. Вам поможет HTTPS/Socks прокси, VPN или Tor
![Image alt](https://github.com/KirillNik/BlockCheck/blob/master/1.jpg)
